# Tugas1_PBO-
Kalkulator 
/* 
  * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license 
  * Click nbfs://nbhost/SystemFileSystem/Templates/GUIForms/JFrame.java to edit this template 
  */ 
  
 /** 
  * 
  * @author miska 
  */ 
 public class kalkulatornunu extends javax.swing.JFrame { 
     String angka; 
     double jumlah, bil1, bil2; 
     int pilih; 
  
     /** 
      * Creates new form kalkulatornunu 
      */ 
     public kalkulatornunu() { 
         initComponents(); 
         angka = ""; 
     } 
  
     /** 
      * This method is called from within the constructor to initialize the form. 
      * WARNING: Do NOT modify this code. The content of this method is always 
      * regenerated by the Form Editor. 
      */ 
     @SuppressWarnings("unchecked") 
     // <editor-fold defaultstate="collapsed" desc="Generated Code">//GEN-BEGIN:initComponents 
     private void initComponents() { 
  
         jPanel1 = new javax.swing.JPanel(); 
         tampilHasil = new javax.swing.JTextField(); 
         btnhapus = new javax.swing.JButton(); 
         btnpersen = new javax.swing.JButton(); 
         btnbagi = new javax.swing.JButton(); 
         angka7 = new javax.swing.JButton(); 
         angka8 = new javax.swing.JButton(); 
         angka9 = new javax.swing.JButton(); 
         btnkali = new javax.swing.JButton(); 
         angka4 = new javax.swing.JButton(); 
         angka5 = new javax.swing.JButton(); 
         angka6 = new javax.swing.JButton(); 
         btnkurang = new javax.swing.JButton(); 
         angka1 = new javax.swing.JButton(); 
         angka2 = new javax.swing.JButton(); 
         angka3 = new javax.swing.JButton(); 
         btntambah = new javax.swing.JButton(); 
         angka0 = new javax.swing.JButton(); 
         btntitik = new javax.swing.JButton(); 
         btnsamadengan = new javax.swing.JButton(); 
  
         setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE); 
  
         tampilHasil.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 tampilHasilActionPerformed(evt); 
             } 
         }); 
  
         btnhapus.setText("("); 
         btnhapus.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 btnhapusActionPerformed(evt); 
             } 
         }); 
  
         btnpersen.setText("%"); 
         btnpersen.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 btnpersenActionPerformed(evt); 
             } 
         }); 
  
         btnbagi.setText("/"); 
         btnbagi.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 btnbagiActionPerformed(evt); 
             } 
         }); 
  
         angka7.setText("7"); 
         angka7.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka7ActionPerformed(evt); 
             } 
         }); 
  
         angka8.setText("8"); 
         angka8.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka8ActionPerformed(evt); 
             } 
         }); 
  
         angka9.setText("9"); 
         angka9.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka9ActionPerformed(evt); 
             } 
         }); 
  
         btnkali.setText("x"); 
         btnkali.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 btnkaliActionPerformed(evt); 
             } 
         }); 
  
         angka4.setText("4"); 
         angka4.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka4ActionPerformed(evt); 
             } 
         }); 
  
         angka5.setText("5"); 
         angka5.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka5ActionPerformed(evt); 
             } 
         }); 
  
         angka6.setText("6"); 
         angka6.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka6ActionPerformed(evt); 
             } 
         }); 
  
         btnkurang.setText("-"); 
         btnkurang.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 btnkurangActionPerformed(evt); 
             } 
         }); 
  
         angka1.setText("1"); 
         angka1.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka1ActionPerformed(evt); 
             } 
         }); 
  
         angka2.setText("2"); 
         angka2.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka2ActionPerformed(evt); 
             } 
         }); 
  
         angka3.setText("3"); 
         angka3.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka3ActionPerformed(evt); 
             } 
         }); 
  
         btntambah.setText("+"); 
         btntambah.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 btntambahActionPerformed(evt); 
             } 
         }); 
  
         angka0.setText("0"); 
         angka0.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 angka0ActionPerformed(evt); 
             } 
         }); 
  
         btntitik.setText("."); 
         btntitik.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 btntitikActionPerformed(evt); 
             } 
         }); 
  
         btnsamadengan.setText("="); 
         btnsamadengan.addActionListener(new java.awt.event.ActionListener() { 
             public void actionPerformed(java.awt.event.ActionEvent evt) { 
                 btnsamadenganActionPerformed(evt); 
             } 
         }); 
  
         javax.swing.GroupLayout jPanel1Layout = new javax.swing.GroupLayout(jPanel1); 
         jPanel1.setLayout(jPanel1Layout); 
         jPanel1Layout.setHorizontalGroup( 
             jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING) 
             .addGroup(jPanel1Layout.createSequentialGroup() 
                 .addGap(21, 21, 21) 
                 .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING) 
                     .addGroup(jPanel1Layout.createSequentialGroup() 
                         .addComponent(angka0, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE) 
                         .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                         .addComponent(btntitik, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                         .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                         .addComponent(btnsamadengan, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                     .addGroup(jPanel1Layout.createSequentialGroup() 
                         .addComponent(angka1, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                         .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                         .addComponent(angka2, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                         .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                         .addComponent(angka3, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                         .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                         .addComponent(btntambah, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                     .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING) 
                         .addGroup(jPanel1Layout.createSequentialGroup() 
                             .addComponent(angka4, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                             .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                             .addComponent(angka5, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                             .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                             .addComponent(angka6, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                             .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                             .addComponent(btnkurang, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                         .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING) 
                             .addGroup(jPanel1Layout.createSequentialGroup() 
                                 .addComponent(angka7, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                                 .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                                 .addComponent(angka8, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                                 .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                                 .addComponent(angka9, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                                 .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                                 .addComponent(btnkali, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                             .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false) 
                                 .addComponent(tampilHasil) 
                                 .addGroup(jPanel1Layout.createSequentialGroup() 
                                     .addComponent(btnhapus, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE) 
                                     .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                                     .addComponent(btnpersen, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE) 
                                     .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED) 
                                     .addComponent(btnbagi, javax.swing.GroupLayout.PREFERRED_SIZE, 52, javax.swing.GroupLayout.PREFERRED_SIZE)))))) 
                 .addContainerGap(21, Short.MAX_VALUE)) 
         ); 
         jPanel1Layout.setVerticalGroup( 
             jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING) 
             .addGroup(jPanel1Layout.createSequentialGroup() 
                 .addGap(23, 23, 23) 
                 .addComponent(tampilHasil, javax.swing.GroupLayout.PREFERRED_SIZE, 71, javax.swing.GroupLayout.PREFERRED_SIZE) 
                 .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED) 
                 .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE) 
                     .addComponent(btnhapus, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(btnpersen, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(btnbagi, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                 .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED) 
                 .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE) 
                     .addComponent(angka7, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(angka8, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(angka9, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(btnkali, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                 .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED) 
                 .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE) 
                     .addComponent(angka4, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(angka5, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(angka6, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(btnkurang, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                 .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED) 
                 .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE) 
                     .addComponent(angka1, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(angka2, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(angka3, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(btntambah, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                 .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED) 
                 .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE) 
                     .addComponent(angka0, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(btntitik, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE) 
                     .addComponent(btnsamadengan, javax.swing.GroupLayout.PREFERRED_SIZE, 39, javax.swing.GroupLayout.PREFERRED_SIZE)) 
                 .addContainerGap(24, Short.MAX_VALUE)) 
         ); 
  
         javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane()); 
         getContentPane().setLayout(layout); 
         layout.setHorizontalGroup( 
             layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING) 
             .addGroup(layout.createSequentialGroup() 
                 .addComponent(jPanel1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE) 
                 .addGap(0, 6, Short.MAX_VALUE)) 
         ); 
         layout.setVerticalGroup( 
             layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING) 
             .addComponent(jPanel1, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE) 
         ); 
  
         pack(); 
     }// </editor-fold>//GEN-END:initComponents 
  
     private void tampilHasilActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_tampilHasilActionPerformed 
         // TODO add your handling code here: 
     }//GEN-LAST:event_tampilHasilActionPerformed 
  
     private void btnhapusActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_btnhapusActionPerformed 
 tampilHasil.setText(angka); 
         bil1 = 0.0; 
         bil2 = 0.0; 
         jumlah = 0.0; 
         angka = "";        
     }//GEN-LAST:event_btnhapusActionPerformed 
  
     private void btnpersenActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_btnpersenActionPerformed 
 bil1 = Double.parseDouble(angka); 
         tampilHasil.setText("%"); 
         angka = ""; 
         pilih = 5;        
     }//GEN-LAST:event_btnpersenActionPerformed 
  
     private void btnbagiActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_btnbagiActionPerformed 
 bil1 = Double.parseDouble(angka); 
         tampilHasil.setText("/"); 
         angka = ""; 
         pilih = 4;         
     }//GEN-LAST:event_btnbagiActionPerformed 
  
     private void angka7ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka7ActionPerformed 
 angka += "7"; 
         tampilHasil.setText(angka);         
     }//GEN-LAST:event_angka7ActionPerformed 
  
     private void angka8ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka8ActionPerformed 
 angka += "8"; 
         tampilHasil.setText(angka);         
     }//GEN-LAST:event_angka8ActionPerformed 
  
     private void angka9ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka9ActionPerformed 
        angka = "9"; 
         tampilHasil.setText(angka); 
     }//GEN-LAST:event_angka9ActionPerformed 
  
     private void btnkaliActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_btnkaliActionPerformed 
 bil1 = Double.parseDouble(angka); 
         tampilHasil.setText("x"); 
         angka = ""; 
         pilih = 3;         
     }//GEN-LAST:event_btnkaliActionPerformed 
  
     private void angka4ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka4ActionPerformed 
         angka += "4"; 
         tampilHasil.setText(angka); 
     }//GEN-LAST:event_angka4ActionPerformed 
  
     private void angka5ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka5ActionPerformed 
 angka += "5"; 
         tampilHasil.setText(angka);         
     }//GEN-LAST:event_angka5ActionPerformed 
  
     private void angka6ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka6ActionPerformed 
 angka += "6"; 
         tampilHasil.setText(angka);         
     }//GEN-LAST:event_angka6ActionPerformed 
  
     private void btnkurangActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_btnkurangActionPerformed 
 bil1 = Double.parseDouble(angka); 
         tampilHasil.setText("-"); 
         angka = ""; 
         pilih = 2;         
     }//GEN-LAST:event_btnkurangActionPerformed 
  
     private void angka1ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka1ActionPerformed 
 angka += "1"; 
         tampilHasil.setText(angka);         
     }//GEN-LAST:event_angka1ActionPerformed 
  
     private void angka2ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka2ActionPerformed 
 angka += "2"; 
         tampilHasil.setText(angka);         
     }//GEN-LAST:event_angka2ActionPerformed 
  
     private void angka3ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka3ActionPerformed 
 angka += "3"; 
         tampilHasil.setText(angka);         
     }//GEN-LAST:event_angka3ActionPerformed 
  
     private void btntambahActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_btntambahActionPerformed 
         bil1 = Double.parseDouble(angka); 
         tampilHasil.setText("+"); 
         angka = ""; 
         pilih = 1; 
     }//GEN-LAST:event_btntambahActionPerformed 
  
     private void angka0ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_angka0ActionPerformed 
         angka += "0"; 
         tampilHasil.setText(angka); 
     }//GEN-LAST:event_angka0ActionPerformed 
  
     private void btntitikActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_btntitikActionPerformed 
         angka += ","; 
         tampilHasil.setText(angka); 
     }//GEN-LAST:event_btntitikActionPerformed 
  
     private void btnsamadenganActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event_btnsamadenganActionPerformed 
     switch(pilih){ 
         case 1: 
             bil2=Double.parseDouble(angka); 
             jumlah = bil1+bil2; 
             angka=Double.toString(jumlah); 
             tampilHasil.setText(angka); 
             break; 
         case 2: 
             bil2=Double.parseDouble(angka); 
             jumlah = bil1-bil2; 
             angka=Double.toString(jumlah); 
             tampilHasil.setText(angka); 
             break; 
         case 3: 
             bil2=Double.parseDouble(angka); 
             jumlah = bil1*bil2; 
             angka=Double.toString(jumlah); 
             tampilHasil.setText(angka); 
             break; 
         case 4: 
             bil2=Double.parseDouble(angka); 
             jumlah = bil1/bil2; 
             angka=Double.toString(jumlah); 
             tampilHasil.setText(angka); 
             break; 
         case 5: 
             bil2=Double.parseDouble(angka); 
             jumlah = bil1%bil2; 
             angka=Double.toString(jumlah); 
             tampilHasil.setText(angka); 
             break; 
     } 
     }//GEN-LAST:event_btnsamadenganActionPerformed 
  
     /** 
      * @param args the command line arguments 
      */ 
     public static void main(String args[]) { 
         /* Set the Nimbus look and feel */ 
         //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) "> 
         /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel. 
          * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html  
          */ 
         try { 
             for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) { 
                 if ("Nimbus".equals(info.getName())) { 
                     javax.swing.UIManager.setLookAndFeel(info.getClassName()); 
                     break; 
                 } 
             } 
         } catch (ClassNotFoundException ex) { 
             java.util.logging.Logger.getLogger(kalkulatornunu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex); 
         } catch (InstantiationException ex) { 
             java.util.logging.Logger.getLogger(kalkulatornunu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex); 
         } catch (IllegalAccessException ex) { 
             java.util.logging.Logger.getLogger(kalkulatornunu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex); 
         } catch (javax.swing.UnsupportedLookAndFeelException ex) { 
             java.util.logging.Logger.getLogger(kalkulatornunu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex); 
         } 
         //</editor-fold> 
  
         /* Create and display the form */ 
         java.awt.EventQueue.invokeLater(new Runnable() { 
             public void run() { 
                 new kalkulatornunu().setVisible(true); 
             } 
         }); 
     } 
  
     // Variables declaration - do not modify//GEN-BEGIN:variables 
     private javax.swing.JButton angka0; 
     private javax.swing.JButton angka1; 
     private javax.swing.JButton angka2; 
     private javax.swing.JButton angka3; 
     private javax.swing.JButton angka4; 
     private javax.swing.JButton angka5; 
     private javax.swing.JButton angka6; 
     private javax.swing.JButton angka7; 
     private javax.swing.JButton angka8; 
     private javax.swing.JButton angka9; 
     private javax.swing.JButton btnbagi; 
     private javax.swing.JButton btnhapus; 
     private javax.swing.JButton btnkali; 
     private javax.swing.JButton btnkurang; 
     private javax.swing.JButton btnpersen; 
     private javax.swing.JButton btnsamadengan; 
     private javax.swing.JButton btntambah; 
     private javax.swing.JButton btntitik; 
     private javax.swing.JPanel jPanel1; 
     private javax.swing.JTextField tampilHasil; 
     // End of variables declaration//GEN-END:variables 
 }
