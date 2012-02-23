# ess-smart-underscore.el --- Ess Smart Underscore

* Filename: ess-smart-underscore.el
* Description: ess-smart-underscore
* Author: Matthew L. Fidler
* Maintainer: Matthew Fidler
* Created: Thu Jul 14 11:04:42 2011 (-0500)
* Version: 0.73
* Last-Updated: Wed Feb 22 20:55:23 2012 (-0600)
    * By:  Matthew L. Fidler
    * Update #:  126
* URL: http://github.com/mlf176f2/ess-smart-underscore.el
* Keywords: ESS, underscore
* Compatibility:

Features that might be required by this library:
;;   `custom', `easymenu', `ess', `ess-compat', `ess-custom',
  `font-lock', `syntax', `widget'.
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;; Commentary:

 To use, put (require 'ess-smart-underscore) in your ~/.emacs file

---------------------------------------
;;; Change Log:
22-Feb-2012    Matthew L. Fidler  
   Last-Updated: Wed Feb 22 20:27:04 2012 (-0600) #120 (Matthew L. Fidler)
   Support unbalanced sexps.
02-Feb-2012    Matthew L. Fidler  
   Last-Updated: Thu Feb  2 21:06:52 2012 (-0600) #117 (Matthew L. Fidler)
   Took out auto-installing.  Most package managers don't want you
   to do this.
03-Aug-2011    Matthew L. Fidler  
   Last-Updated: Wed Aug  3 15:05:15 2011 (-0500) #112 (Matthew L. Fidler)
   Bug fix for parenthetical statement
20-Jul-2011    Matthew L. Fidler  
   Last-Updated: Wed Jul 20 15:20:10 2011 (-0500) #101 (Matthew L. Fidler)

   Changed to allow underscore instead of assign when inside a
   parenthetical statement.

15-Jul-2011    Matthew L. Fidler
   Last-Updated: Fri Jul 15 11:34:52 2011 (-0500) #90 (Matthew L. Fidler)
   Bug fix for d[d$CMT == 2,"DV"] _ to produce d[d$CMT == 2,"DV"] <-


---------------------------------------

Licensed under the [GPL version 3](http://www.gnu.org/licenses/) or later.

---------------------------------------


