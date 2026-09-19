<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inPtpMd)"><path fill="url(#iVMKhkc)" class="re9mjmbgd"/><path fill="url(#inFjTld)" class="re9mjmbgd"/></g><g filter="url(#iTyvpye)"><path fill="url(#ikWGBhc)" class="vq9gri74c"/><path fill="url(#iFidsEc)" class="vq9gri74c"/><path fill="url(#iD3OSmb)" class="vq9gri74c"/></g><g filter="url(#ixubxgU)"><path fill="url(#i82GXic)" class="bntwvf6ie"/></g><g filter="url(#i0iQcIb)"><path fill="url(#iiKubcc)" class="j10x9le7y"/><path fill="url(#iLZlOrd)" class="j10x9le7y"/><path fill="url(#ihcSNCd)" class="j10x9le7y"/></g><g filter="url(#irNoVYc)"><path fill="url(#iIcIMhb)" class="zpyxxpzpr"/><path fill="url(#idOomRd)" class="zpyxxpzpr"/></g><g filter="url(#ixsKgWb)"><path fill="url(#ifnBrEd)" class="zqz300wxy"/><path fill="url(#iDtgsnc)" class="zqz300wxy"/><path fill="url(#i8Zlrid)" class="zqz300wxy"/></g><g filter="url(#iNjFV2l)"><path class="rsmz6pb-r"/><path fill="url(#i2Rlkvc)" class="we0_ydm6g"/><path fill="url(#iG5a4ID)" class="we0_ydm6g"/></g><g filter="url(#i8jATno)"><path fill="url(#iYO29ee)" class="kx4qp6bkg"/></g><g filter="url(#iQQRrdb)"><rect class="eky3n568j"/></g><g filter="url(#iWYGgze)"><rect class="fxbi-pbue"/></g><g filter="url(#iyO57ee)"><rect class="caobr2v1g"/></g><g filter="url(#iH2xFBd)"><rect class="a4cs2068h"/></g><g filter="url(#ibl1UpK)"><rect class="gt3wxybry"/></g><g filter="url(#iBB4bze)"><rect class="zin7g1kgz"/></g><g filter="url(#iZlsBRw)"><rect class="itzw6t0ka"/></g><g filter="url(#igkVq3b)"><rect class="x5mymw7jf"/></g><g filter="url(#iBtz7uw)"><rect class="mylny1bbk"/></g><g filter="url(#iKpFoRd)"><path fill="url(#iET7Ubd)" class="qxleo-b2c"/></g><g filter="url(#iFNG4dS)"><path fill="url(#iMB9Q6c)" class="vt_jpesnn"/></g><g filter="url(#imE4Gse)"><path fill="url(#iR6QBdd)" class="ffvb7dbei"/></g><defs><filter id="inPtpMd" width="28.619" height="5.822" x="2.016" y="24.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.254902 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.180392 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19136" result="effect2_innerShadow_18_19136"/></filter><filter id="iTyvpye" width="28.672" height="8.391" x="2.172" y="6.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.254902 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19136"/></filter><filter id="ixubxgU" width="19.844" height="5.031" x="9.75" y="7.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19136" stdDeviation=".5"/></filter><filter id="i0iQcIb" width="8.219" height="6.352" x="2.195" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19136" stdDeviation=".25"/></filter><filter id="irNoVYc" width="8.219" height="6.352" x="21.539" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19136" stdDeviation=".25"/></filter><filter id="ixsKgWb" width="8.203" height="2.938" x="2.015" y="13.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.121569 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19136"/></filter><filter id="iNjFV2l" width="8.203" height="2.938" x="21.781" y="13.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.133333 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19136"/></filter><filter id="i8jATno" width="28.469" height="15.442" x="2.016" y="10.917" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19136"/></filter><filter id="iQQRrdb" width="3.02" height="3.02" x="14.34" y="16.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.152941 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="iWYGgze" width="3.02" height="3.02" x="17.34" y="16.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.152941 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="iyO57ee" width="3.02" height="3.02" x="11.34" y="16.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.152941 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="iH2xFBd" width="3.02" height="3.02" x="14.34" y="19.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.152941 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="ibl1UpK" width="3.02" height="3.02" x="14.34" y="22.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.117647 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="iBB4bze" width="3.02" height="3.02" x="17.34" y="19.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.152941 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="iZlsBRw" width="3.02" height="3.02" x="17.34" y="22.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.117647 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="igkVq3b" width="3.02" height="3.02" x="11.34" y="19.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.152941 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="iBtz7uw" width="3.02" height="3.02" x="11.34" y="22.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.117647 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19136"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19136" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19136"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.658824 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19136" result="effect3_innerShadow_18_19136"/></filter><filter id="iKpFoRd" width="12.935" height="13.182" x="18.032" y="13.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19136" stdDeviation="1"/></filter><filter id="iFNG4dS" width="1.534" height="3.436" x="10.583" y="11.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19136" stdDeviation=".25"/></filter><filter id="imE4Gse" width="1.534" height="3.436" x="20.642" y="11.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19136" stdDeviation=".25"/></filter><linearGradient id="iVMKhkc" x1="16" x2="16" y1="26.867" y2="30.031" gradientUnits="userSpaceOnUse"><stop class="grhqzg6ew"/><stop offset="1" class="pmjt1k7oo"/></linearGradient><linearGradient id="inFjTld" x1="29.985" x2="28.309" y1="28.009" y2="28.009" gradientUnits="userSpaceOnUse"><stop offset=".215" class="oerb-bc9o"/><stop offset="1" class="zvorb1whu"/></linearGradient><linearGradient id="ikWGBhc" x1="16.008" x2="16.008" y1="8.313" y2="14.984" gradientUnits="userSpaceOnUse"><stop class="aepoiz3ll"/><stop offset="1" class="lktivgb8p"/></linearGradient><linearGradient id="i82GXic" x1="20.031" x2="19.672" y1="8.156" y2="11.063" gradientUnits="userSpaceOnUse"><stop offset=".392" class="sh93u75ip"/><stop offset="1" class="vqgslcgps"/></linearGradient><linearGradient id="ifnBrEd" x1="7.969" x2="2.015" y1="15.531" y2="15.531" gradientUnits="userSpaceOnUse"><stop class="npxgv98ol"/><stop offset="1" class="stu8imhty"/></linearGradient><linearGradient id="i8Zlrid" x1="6.117" x2="6.117" y1="14.047" y2="14.438" gradientUnits="userSpaceOnUse"><stop class="qxefzsb0y"/><stop offset="1" class="qldenjbkk"/></linearGradient><linearGradient id="iG5a4ID" x1="25.883" x2="25.883" y1="14.047" y2="14.438" gradientUnits="userSpaceOnUse"><stop class="qxefzsb0y"/><stop offset="1" class="qldenjbkk"/></linearGradient><linearGradient id="iYO29ee" x1="16" x2="16" y1="13.938" y2="25.375" gradientUnits="userSpaceOnUse"><stop class="x0xcdub_w"/><stop offset="1" class="xyehb4bmc"/></linearGradient><linearGradient id="iET7Ubd" x1="22.006" x2="29.324" y1="15.242" y2="24.397" gradientUnits="userSpaceOnUse"><stop class="g00hgc-gl"/><stop offset="1" class="wkvuyigyu"/></linearGradient><linearGradient id="iMB9Q6c" x1="11.351" x2="11.351" y1="11.611" y2="14.749" gradientUnits="userSpaceOnUse"><stop offset=".444" class="nw7r8crxp"/><stop offset="1" class="okkbseaij"/></linearGradient><linearGradient id="iR6QBdd" x1="21.41" x2="21.41" y1="11.611" y2="14.749" gradientUnits="userSpaceOnUse"><stop offset=".444" class="nw7r8crxp"/><stop offset="1" class="okkbseaij"/></linearGradient><radialGradient id="iFidsEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5 -9.60156 0 16.008 13.188)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="bf_w90myy"/><stop offset="1" class="zq44y5gih"/></radialGradient><radialGradient id="iD3OSmb" cx="0" cy="0" r="1" gradientTransform="rotate(113.051 .422 10.026)scale(3.1924 2.06567)" gradientUnits="userSpaceOnUse"><stop class="yq2fm7bvt"/><stop offset="1" class="aio4iyxub"/></radialGradient><radialGradient id="iiKubcc" cx="0" cy="0" r="1" gradientTransform="rotate(-90 10.49 4.458)scale(4.9714)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="a79x7bbjf"/><stop offset="1" class="hcsrvubqe"/></radialGradient><radialGradient id="iLZlOrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.34375 1.40625 0 7.813 14.375)" gradientUnits="userSpaceOnUse"><stop class="p4mtbh-us"/><stop offset="1" class="il5778bwn"/></radialGradient><radialGradient id="ihcSNCd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 1.40624 -3.73273 -3.06915 8.906 10.531)" gradientUnits="userSpaceOnUse"><stop class="tl0xzreat"/><stop offset="1" class="m_6d594rr"/></radialGradient><radialGradient id="iIcIMhb" cx="0" cy="0" r="1" gradientTransform="rotate(-67.1 22.87 -10.956)scale(4.77502)" gradientUnits="userSpaceOnUse"><stop class="waj011tqv"/><stop offset="1" class="hcsrvubqe"/></radialGradient><radialGradient id="idOomRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.65625 4.21875 0 27.406 14.219)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="p0de7nv1m"/><stop offset="1" class="il5778bwn"/></radialGradient><radialGradient id="iDtgsnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.64063 -4.5 0 7.5 13.5)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="tyw0uonjf"/><stop offset="1" class="za-chebpo"/></radialGradient><radialGradient id="i2Rlkvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09375 -4.10156 0 27.735 14.047)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="gb-fa0q0h"/><stop offset="1" class="fh3x7ebmg"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:telephone" /></template>
<style>
.a4cs2068h {
  width: 2.02px;
  height: 2.02px;
  x: 14.99px;
  y: 20.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.a79x7bbjf {
  stop-color: var(--svg-color--bb2844, #BB2844);
}

.aepoiz3ll {
  stop-color: var(--svg-color--e6307b, #E6307B);
}

.aio4iyxub {
  stop-color: var(--svg-color--ca354d, #CA354D);
  stop-opacity: 0;
}

.bf_w90myy {
  stop-color: var(--svg-color--881d3b, #881D3B);
}

.bntwvf6ie {
  d: path("M10.75 8.906h14.813a3.03 3.03 0 0 1 3.03 3.031H10.75z");
}

.caobr2v1g {
  width: 2.02px;
  height: 2.02px;
  x: 11.99px;
  y: 17.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.eky3n568j {
  width: 2.02px;
  height: 2.02px;
  x: 14.99px;
  y: 17.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.ffvb7dbei {
  d: path("M21.142 11.611h.534v2.436h-.534z");
}

.fh3x7ebmg {
  stop-color: var(--svg-color--ce6272, #CE6272);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxbi-pbue {
  width: 2.02px;
  height: 2.02px;
  x: 17.99px;
  y: 17.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.g00hgc-gl {
  stop-color: var(--svg-color--ff449d, #FF449D);
}

.gb-fa0q0h {
  stop-color: var(--svg-color--ce6272, #CE6272);
}

.grhqzg6ew {
  stop-color: var(--svg-color--c53956, #C53956);
}

.gt3wxybry {
  width: 2.02px;
  height: 2.02px;
  x: 14.99px;
  y: 23.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.hcsrvubqe {
  stop-color: var(--svg-color--bb2844, #BB2844);
  stop-opacity: 0;
}

.il5778bwn {
  stop-color: var(--svg-color--de596c, #DE596C);
  stop-opacity: 0;
}

.itzw6t0ka {
  width: 2.02px;
  height: 2.02px;
  x: 17.99px;
  y: 23.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.j10x9le7y {
  d: path("M9.466 15.14a3.61 3.61 0 1 0-6.324 0z");
}

.kx4qp6bkg {
  d: path("M20.016 11.867a.75.75 0 0 1 .75-.75h.492a.75.75 0 0 1 .75.75v1.617a.5.5 0 0 0 .5.5h.145a2.5 2.5 0 0 1 1.944.929l3.333 4.235c1.294 1.602 2.055 3.553 2.055 5.613v.098c0 .829-.93 1.5-2.188 1.5H4.203c-1.258 0-2.187-.671-2.187-1.5v-.099c0-2.059.76-4.01 2.054-5.612l3.333-4.235a2.5 2.5 0 0 1 1.944-.929h.145a.5.5 0 0 0 .5-.5v-1.617a.75.75 0 0 1 .75-.75h.492a.75.75 0 0 1 .75.75v1.617a.5.5 0 0 0 .5.5h7.032a.5.5 0 0 0 .5-.5z");
}

.lktivgb8p {
  stop-color: var(--svg-color--c02946, #C02946);
}

.m_6d594rr {
  stop-color: var(--svg-color--e15875, #E15875);
  stop-opacity: 0;
}

.mylny1bbk {
  width: 2.02px;
  height: 2.02px;
  x: 11.99px;
  y: 23.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.npxgv98ol {
  stop-color: var(--svg-color--a11e45, #A11E45);
}

.nw7r8crxp {
  stop-color: var(--svg-color--ff64b1, #FF64B1);
}

.oerb-bc9o {
  stop-color: var(--svg-color--dd5d6d, #DD5D6D);
}

.okkbseaij {
  stop-color: var(--svg-color--ff64b1, #FF64B1);
  stop-opacity: 0;
}

.p0de7nv1m {
  stop-color: var(--svg-color--e25b6e, #E25B6E);
}

.p4mtbh-us {
  stop-color: var(--svg-color--de596c, #DE596C);
}

.pmjt1k7oo {
  stop-color: var(--svg-color--c53555, #C53555);
}

.qldenjbkk {
  stop-color: var(--svg-color--b1203e, #B1203E);
  stop-opacity: 0;
}

.qxefzsb0y {
  stop-color: var(--svg-color--b1203e, #B1203E);
}

.qxleo-b2c {
  d: path("M23.65 15.05h-3.618l8.936 9.183c0-1.842-.695-3.271-1.042-3.755z");
}

.re9mjmbgd {
  d: path("M2.016 24.86v3.471a1.7 1.7 0 0 0 1.7 1.7h24.569a1.7 1.7 0 0 0 1.7-1.7V24.86c0 .829-.93 1.5-2.188 1.5H4.203c-1.258 0-2.187-.671-2.187-1.5");
}

.rsmz6pb-r {
  fill: var(--svg-color--b42e50, #B42E50);
  d: path("M29.984 14.447a.4.4 0 0 0-.4-.4h-7.803v2.187h6.803a1.4 1.4 0 0 0 1.4-1.4z");
}

.sh93u75ip {
  stop-color: var(--svg-color--ee507f, #EE507F);
}

.stu8imhty {
  stop-color: var(--svg-color--98484c, #98484C);
}

.tl0xzreat {
  stop-color: var(--svg-color--e15875, #E15875);
}

.tyw0uonjf {
  stop-color: var(--svg-color--c25d6c, #C25D6C);
}

.vq9gri74c {
  d: path("M9.672 7.094c-4.422 0-7.328 3.25-7.5 7.5v.39h8.84l.62-1.75q.021-.02.04-.043c.111-.126.278-.316 1.46-.316h5.774c.68 0 1.436.081 2.055.563c.332.257.345.888.235 1.546h8.648v-.39c-.266-4.313-3.047-7.5-7.5-7.5z");
}

.vqgslcgps {
  stop-color: var(--svg-color--ee507f, #EE507F);
  stop-opacity: 0;
}

.vt_jpesnn {
  d: path("M11.083 11.611h.534v2.436h-.534z");
}

.waj011tqv {
  stop-color: var(--svg-color--bf0c35, #BF0C35);
}

.we0_ydm6g {
  d: path("M29.984 14.447a.4.4 0 0 0-.4-.4h-7.803v2.187h6.803a1.4 1.4 0 0 0 1.4-1.4z");
}

.wkvuyigyu {
  stop-color: var(--svg-color--ff6590, #FF6590);
}

.x0xcdub_w {
  stop-color: var(--svg-color--fa2e92, #FA2E92);
}

.x5mymw7jf {
  width: 2.02px;
  height: 2.02px;
  x: 11.99px;
  y: 20.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.xyehb4bmc {
  stop-color: var(--svg-color--ec2c6a, #EC2C6A);
}

.yq2fm7bvt {
  stop-color: var(--svg-color--8a011b, #8A011B);
}

.za-chebpo {
  stop-color: var(--svg-color--c25d6c, #C25D6C);
  stop-opacity: 0;
}

.zin7g1kgz {
  width: 2.02px;
  height: 2.02px;
  x: 17.99px;
  y: 20.008px;
  fill: var(--svg-color--e3d8ec, #E3D8EC);
  rx: 0.4px;
}

.zpyxxpzpr {
  d: path("M22.487 15.14a3.61 3.61 0 1 1 6.324 0z");
}

.zq44y5gih {
  stop-color: var(--svg-color--bd0639, #BD0639);
  stop-opacity: 0;
}

.zqz300wxy {
  d: path("M2.015 14.447a.4.4 0 0 1 .4-.4h7.804v2.187H3.416a1.4 1.4 0 0 1-1.4-1.4z");
}

.zvorb1whu {
  stop-color: var(--svg-color--ca3a57, #CA3A57);
  stop-opacity: 0;
}

</style>
