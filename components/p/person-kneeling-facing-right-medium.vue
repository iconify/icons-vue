<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iALJD8c)"><path class="jtq5yvb4h"/></g><g filter="url(#i7wcodd)"><path stroke="url(#imJxWQb)" class="tvmdpsxgz"/></g><path fill="url(#izrJNLK)" class="r43ardy0p"/><g filter="url(#iH724SN)"><path class="ukun0zr2w"/></g><path fill="url(#iDk8M4b)" class="syui_3c1e"/><path fill="url(#iqhAKHM)" class="syui_3c1e"/><path fill="url(#ia84Ord)" class="ej3erkgif"/><g filter="url(#iGbhiNd)"><path class="o4cae1ltj"/><path fill="url(#iGhc6hd)" class="g8yxf5b0p"/><path fill="url(#iPrKbZZ)" class="g8yxf5b0p"/></g><g filter="url(#iyakSNb)"><path class="qvtw3_t5d"/><path fill="url(#iMMpeQw)" class="oledkbbaw"/><path fill="url(#iNNBhia)" class="oledkbbaw"/></g><path fill="url(#ib5ZaHd)" transform="scale(-1 1)rotate(-14.867 27.08 74.13)" class="ofkpelbcu"/><path fill="url(#iMWibqd)" transform="scale(-1 1)rotate(-14.867 27.08 74.13)" class="ofkpelbcu"/><path fill="url(#i0nBRNb)" transform="scale(-1 1)rotate(-14.867 27.08 74.13)" class="ofkpelbcu"/><path fill="url(#itIClMe)" class="m53_03cvw"/><path fill="url(#i6W8Ncb)" class="m53_03cvw"/><path fill="url(#iKrR2sb)" class="m53_03cvw"/><path fill="url(#irfJ54c)" class="yihvobc3s"/><path fill="url(#iVYP5Ac)" class="yihvobc3s"/><g filter="url(#i6YkHJa)"><path fill="url(#iioxkxc)" class="ulnh2gbeq"/><path fill="url(#iMOd48d)" class="ulnh2gbeq"/><path fill="url(#iLIZEtc)" class="ulnh2gbeq"/><path fill="url(#i9zygSb)" class="ulnh2gbeq"/></g><g filter="url(#i8kjqCe)"><path fill="url(#iwhVyme)" class="qyjlr9bhz"/><path fill="url(#iBUtVMt)" class="qyjlr9bhz"/><path fill="url(#ioahfQe)" class="qyjlr9bhz"/></g><path fill="url(#izBGrLc)" class="xmz1p-bxa"/><path fill="url(#iBYKAtd)" class="xmz1p-bxa"/><path fill="url(#iUOtENd)" class="xmz1p-bxa"/><path clip-rule="evenodd" class="ycat-rbnu"/><g filter="url(#iuEcADc)"><path clip-rule="evenodd" class="bw-kmqb2y"/></g><path class="h-dycq2ze"/><path fill="url(#iF3TrDe)" class="ad3hwtbmq"/><path fill="url(#i7vSGgd)" class="ccjii0bjm"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -26.252 -40.307)" class="m1l7k9jve"/><g filter="url(#ijwB1dB)"><path class="rr0hthdaj"/><path fill="url(#iAE6u3c)" class="y19y8w5ub"/></g><g filter="url(#ilzZ4de)"><path class="j089ert6g"/></g><g filter="url(#igKSmpd)"><path class="eg1rhdb1d"/></g><path fill="url(#ijeQKkd)" class="nw3j99sey"/><path fill="url(#iXQSMxb)" class="nw3j99sey"/><path fill="url(#i5iySXc)" class="nw3j99sey"/><path fill="url(#iLP4tPd)" class="nw3j99sey"/><g filter="url(#i2Jytxb)"><path fill="url(#ilNxuUb)" class="garbodb5m"/></g><g filter="url(#iXVx7MS)"><path fill="url(#iNV9Ded)" class="jv239dbcz"/></g><defs><radialGradient id="imJxWQb" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.039 9.649)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="izrJNLK" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.776 20.233)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="iqhAKHM" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 19.151 17.904)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="ia84Ord" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.558 18.014)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="ib5ZaHd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80955 4.93989 .09 1.583)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="eitmobczl"/><stop offset="1" class="l5cg6c78h"/></radialGradient><radialGradient id="iMWibqd" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 .923 .84)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="ef2avdbrg"/><stop offset="1" class="ju9-v_r3z"/></radialGradient><radialGradient id="itIClMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 14.323 13.53)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="zgjycebbf"/><stop offset=".849" class="cic7ureox"/></radialGradient><radialGradient id="i6W8Ncb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03122 3.14064 -3.13218 2.02576 14.76 11.655)" gradientUnits="userSpaceOnUse"><stop class="pyqlo9ccb"/><stop offset="1" class="tim0t4m8u"/></radialGradient><radialGradient id="iKrR2sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.838 15.278)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="xu4oisaxz"/><stop offset="1" class="jtmbyac_e"/></radialGradient><radialGradient id="irfJ54c" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 9.116 6.743)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="iVYP5Ac" cx="0" cy="0" r="1" gradientTransform="matrix(.12006 -.29152 .4375 .18019 19.938 8.653)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="iMOd48d" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.681 7.634)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="iLIZEtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 19.578 8.821)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="i9zygSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 18.75 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="iwhVyme" cx="0" cy="0" r="1" gradientTransform="rotate(-141.435 9.956 .265)scale(3.12459 4.73465)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="lbq-lsb6f"/><stop offset="1" class="g-7ivnbav"/></radialGradient><radialGradient id="iBUtVMt" cx="0" cy="0" r="1" gradientTransform="rotate(-144.319 10.77 -.616)scale(1.50012 2.40215)" gradientUnits="userSpaceOnUse"><stop class="tue5drbtp"/><stop offset="1" class="d6crxg3sz"/></radialGradient><radialGradient id="ioahfQe" cx="0" cy="0" r="1" gradientTransform="matrix(.53132 .14843 -.072 .25775 14.97 8.509)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="ja8qkqbty"/><stop offset="1" class="rxuswac8h"/></radialGradient><radialGradient id="izBGrLc" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 9.034 2.55)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="iBYKAtd" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 5.501 10.62)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="iF3TrDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.045 7.708)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i7vSGgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.213 7.73)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iAE6u3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.34375 -.8049 -.04293 15.651 15.274)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="q3uvkbbyl"/><stop offset="1" class="utxluw1tg"/></radialGradient><radialGradient id="ijeQKkd" cx="0" cy="0" r="1" gradientTransform="rotate(-87.255 16.584 -1.3)scale(4.56774 2.32974)" gradientUnits="userSpaceOnUse"><stop class="q-nbb5ezw"/><stop offset="1" class="jqsx2jbza"/></radialGradient><radialGradient id="iXQSMxb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 1.32812 -1.6478 1.08562 15.432 11.389)" gradientUnits="userSpaceOnUse"><stop class="eq7ur_bkf"/><stop offset="1" class="uverm5y1q"/></radialGradient><linearGradient id="iDk8M4b" x1="15.214" x2="15.214" y1="17.811" y2="18.342" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iGhc6hd" x1="20.089" x2="21.073" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="iPrKbZZ" x1="21.526" x2="21.526" y1="27.94" y2="27.569" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iMMpeQw" x1="11.064" x2="10.378" y1="25.029" y2="25.694" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="iNNBhia" x1="8.917" x2="9.132" y1="26.233" y2="26.405" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="i0nBRNb" x1="-.003" x2=".233" y1="1.875" y2="1.869" gradientUnits="userSpaceOnUse"><stop class="a-mj2kbzz"/><stop offset="1" class="ikw2jw0zo"/></linearGradient><linearGradient id="iioxkxc" x1="16.994" x2="19.856" y1="8.376" y2="8.548" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="iUOtENd" x1="17.053" x2="16.904" y1="7.585" y2="7.597" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="i5iySXc" x1="15.886" x2="15.979" y1="15.498" y2="14.248" gradientUnits="userSpaceOnUse"><stop class="ky5pzdbbm"/><stop offset="1" class="giu-ixb2s"/></linearGradient><linearGradient id="iLP4tPd" x1="18.245" x2="17.393" y1="15.209" y2="15.209" gradientUnits="userSpaceOnUse"><stop class="uk2nrwb0k"/><stop offset="1" class="uy34yibrn"/></linearGradient><linearGradient id="ilNxuUb" x1="21.694" x2="15.214" y1="24.826" y2="18.889" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="iNV9Ded" x1="15.5" x2="15.756" y1="7.036" y2="4.114" gradientUnits="userSpaceOnUse"><stop offset=".421" class="sj3owrynx"/><stop offset="1" class="i4z7nbbdt"/></linearGradient><filter id="iALJD8c" width="7.28" height="8.609" x="10.996" y="19.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2100" result="effect2_innerShadow_2_2100"/></filter><filter id="i7wcodd" width="5.734" height="7.279" x="11.071" y="20.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2100" stdDeviation=".25"/></filter><filter id="iH724SN" width="11.64" height="10.135" x="13.28" y="17.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/></filter><filter id="iGbhiNd" width="4.352" height="2.364" x="20.218" y="25.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/></filter><filter id="iyakSNb" width="3.579" height="3.542" x="7.83" y="24.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/></filter><filter id="i6YkHJa" width="4.443" height="5.249" x="15.413" y="5.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.345098 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/></filter><filter id="i8kjqCe" width="5.586" height="5.499" x="14.291" y="3.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.14902 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/></filter><filter id="iuEcADc" width="1.013" height=".568" x="18.181" y="6.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/></filter><filter id="ijwB1dB" width="6.876" height="3.179" x="15.419" y="14.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.403922 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.337255 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2100" result="effect2_innerShadow_2_2100"/></filter><filter id="ilzZ4de" width="1.071" height="1.439" x="21.358" y="17.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.4 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/></filter><filter id="igKSmpd" width="1.196" height="1.065" x="20.878" y="17.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.4 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2100"/></filter><filter id="i2Jytxb" width="8.168" height="8.42" x="14.276" y="18.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2100" stdDeviation=".375"/></filter><filter id="iXVx7MS" width="2.276" height="3.492" x="14.545" y="4.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2100" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-kneeling-facing-right-medium" /></template>
<style>
.a-mj2kbzz {
  stop-color: var(--svg-color--a67a6e, #A67A6E);
}

.ad3hwtbmq {
  d: path("M18.717 7.73v-.004c0-.32.137-.58.306-.58c.17 0 .307.26.307.58v.003z");
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.bw-kmqb2y {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M18.81 6.697a.8.8 0 0 1 .216-.016a.15.15 0 0 0 .037-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.408.173a.15.15 0 0 0 .178.24c.085-.062.19-.1.29-.12");
}

.ccjii0bjm {
  d: path("m18.912 7.73l-.004-.073c0-.185.079-.336.176-.336s.175.15.175.336l-.004.072z");
}

.cic7ureox {
  stop-color: var(--svg-color--e54d24, #E54D24);
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.d6crxg3sz {
  stop-color: var(--svg-color--68514d, #68514D);
  stop-opacity: 0;
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.ef2avdbrg {
  stop-color: var(--svg-color--8e695b, #8E695B);
}

.eg1rhdb1d {
  fill: var(--svg-color--a27b6d, #A27B6D);
  d: path("M21.448 17.744c-.325-.003-.516.179-.57.27c.271.144.499.376.65.567c.1.124.278.169.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.533");
}

.eitmobczl {
  stop-color: var(--svg-color--9b6a61, #9B6A61);
}

.ej3erkgif {
  d: path("M20.293 20.52v-.002c-1.787.442-3.937.808-5.747.261c-1.2-.362-1.266-1.816-1.266-2.875l7.61.079q.4.138.701.336z");
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.eq7ur_bkf {
  stop-color: var(--svg-color--ff9337, #FF9337);
}

.ft5dv1b6b {
  fill: none;
}

.fwheo7gdw {
  stop-color: var(--svg-color--60608e, #60608E);
}

.fy99v1bac {
  stop-color: var(--svg-color--897694, #897694);
}

.g-7ivnbav {
  stop-color: var(--svg-color--583e3b, #583E3B);
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.g8yxf5b0p {
  d: path("M20.23 26.517a6.3 6.3 0 0 1 1.413-.642l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.garbodb5m {
  d: path("m21.683 20.444l-.657 5.492l-.312.125l.43-5.73a.487.487 0 0 0-.482-.528c-.926-.006-3.848 0-4.542 0c-.813 0-1.094-.273-1.094-.648c1.193-.01 4.677-.025 5.664 0s1.04.861.992 1.289");
}

.giu-ixb2s {
  stop-color: var(--svg-color--ef6623, #EF6623);
  stop-opacity: 0;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.h-dycq2ze {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.322 7.73h-.988c0-.392.221-.71.494-.71s.494.318.494.71");
}

.i4z7nbbdt {
  stop-color: var(--svg-color--644a48, #644A48);
  stop-opacity: 0;
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ikw2jw0zo {
  stop-color: var(--svg-color--a67a6e, #A67A6E);
  stop-opacity: 0;
}

.j089ert6g {
  fill: var(--svg-color--9f786d, #9F786D);
  d: path("m21.401 17.147l-.043.633c.233.181.452.427.603.608a.27.27 0 0 0 .346.058a.243.243 0 0 0 .085-.338a3.6 3.6 0 0 0-.99-.961");
}

.ja8qkqbty {
  stop-color: var(--svg-color--5f4745, #5F4745);
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jqsx2jbza {
  stop-color: var(--svg-color--ff8130, #FF8130);
}

.jtmbyac_e {
  stop-color: var(--svg-color--cd5a3b, #CD5A3B);
}

.jtq5yvb4h {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M17.27 25.616c.05-1.838-.196-4.493-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.265c-1.062-.265-2.578-.171-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.141 2.372.086 2.43-2.046");
}

.ju9-v_r3z {
  stop-color: var(--svg-color--8e695b, #8E695B);
  stop-opacity: 0;
}

.jv239dbcz {
  d: path("M16.163 6.01a13 13 0 0 0-.63 1.412a2.9 2.9 0 0 1-.458-2.038c.07-.496.738-.6 1.087-.24c.252.26.168.545 0 .866");
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.ky5pzdbbm {
  stop-color: var(--svg-color--f04d1d, #F04D1D);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.l5cg6c78h {
  stop-color: var(--svg-color--ba8f7c, #BA8F7C);
}

.lbq-lsb6f {
  stop-color: var(--svg-color--503339, #503339);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m53_03cvw {
  d: path("M18.323 13.127c.162 1.15.094 2.637-.016 3.528v1.289h-5.031c.055-2.063.578-4.729 1.367-6.047c.664-1.11 1.422-1.176 2.055-.957c.605.183 1.422.75 1.625 2.187");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.nw3j99sey {
  d: path("M17.724 12.612a1.261 1.261 0 0 0-2.519-.119l-.155 2.775l2.566.152z");
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.o4cae1ltj {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M20.23 26.517a6.3 6.3 0 0 1 1.413-.642l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.ofkpelbcu {
  d: path("M0 0h1.976v2.198H0z");
}

.oledkbbaw {
  d: path("m10.524 24.764l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.179 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.pyqlo9ccb {
  stop-color: var(--svg-color--ff953a, #FF953A);
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.q-nbb5ezw {
  stop-color: var(--svg-color--ea5e20, #EA5E20);
}

.q3uvkbbyl {
  stop-color: var(--svg-color--b98e81, #B98E81);
}

.qvtw3_t5d {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m10.524 24.764l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.179 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.qyjlr9bhz {
  d: path("M19.767 4.593c-.237-.487-.796-.603-1.074-.588c-.86.047-.977.344-1.754.184c-.821-.17-1.226-.121-1.578.039l-.007.003c-.346.157-1.063.483-1.063 1.95c0 1.351.482 2.065.715 2.32l-.046.017c-.232.083-.327.33-.244.561c.072.198.322.311.637.262c.36-.057.625-.106.832-.147a.25.25 0 0 0 .2-.244V7.837c0-.469.33-.749.476-.832c.016-.484.164-.707.406-.824c.401-.194.526-.098 1.485-.157c1.015-.061 1.312-.821 1.015-1.43");
}

.r43ardy0p {
  d: path("M17.27 25.616c.05-1.838-.196-4.493-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.265c-1.062-.265-2.578-.171-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.141 2.372.086 2.43-2.046");
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rr0hthdaj {
  fill: var(--svg-color--ad8375, #AD8375);
  d: path("m17.315 16.076l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.984c.266.391.765.859 2.2.946c1.03.062 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
}

.rxuswac8h {
  stop-color: var(--svg-color--5f4745, #5F4745);
  stop-opacity: 0;
}

.sj3owrynx {
  stop-color: var(--svg-color--644a48, #644A48);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.syui_3c1e {
  d: path("M22.764 21.108c-.137.575-.807 3.427-1.125 4.78c.573.233 1.39.67 2.067 1.009c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.17c-1.787.443-3.937.81-5.747.262c-1.2-.362-1.266-1.816-1.266-2.875l7.61.079a2.726 2.726 0 0 1 1.874 3.125");
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.tim0t4m8u {
  stop-color: var(--svg-color--ff953a, #FF953A);
  stop-opacity: 0;
}

.tue5drbtp {
  stop-color: var(--svg-color--68514d, #68514D);
}

.tvmdpsxgz {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.792 20.592c.138.941.573 3.263 1.239 5.338a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.085c-.689-.243-2.053-.526-3.737-.302");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uk2nrwb0k {
  stop-color: var(--svg-color--d36030, #D36030);
}

.ukun0zr2w {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.764 21.108c-.137.575-.807 3.427-1.125 4.78c.573.233 1.39.67 2.067 1.009c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.17c-1.787.443-3.937.81-5.747.262c-1.2-.362-1.266-1.816-1.266-2.875l7.61.079a2.726 2.726 0 0 1 1.874 3.125");
}

.ulnh2gbeq {
  d: path("M19.828 6.936c-.038-.802-.298-1.188-.42-1.3h-3.732l-.063 3.163c.867 2.122 3.512 2.213 3.907 1.445c.395-.767.353-2.38.308-3.308");
}

.utxluw1tg {
  stop-color: var(--svg-color--b98e81, #B98E81);
  stop-opacity: 0;
}

.uverm5y1q {
  stop-color: var(--svg-color--ff9337, #FF9337);
  stop-opacity: 0;
}

.uy34yibrn {
  stop-color: var(--svg-color--d36030, #D36030);
  stop-opacity: 0;
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xmz1p-bxa {
  d: path("m17.15 8.39l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.xu4oisaxz {
  stop-color: var(--svg-color--cd5a3b, #CD5A3B);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
}

.y19y8w5ub {
  d: path("m17.315 16.076l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.984c.266.391.765.859 2.2.946c1.03.062 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
}

.ycat-rbnu {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M18.577 8.843a.125.125 0 0 0 .001.177c.238.234.583.293.692.305a.125.125 0 1 0 .026-.25c-.094-.009-.367-.061-.543-.234a.125.125 0 0 0-.177.002");
}

.yihvobc3s {
  d: path("M20.052 7.9a1 1 0 0 1-.258-.458h-.18v1.125c.215.137.523.116.614-.09c.078-.175.02-.394-.176-.578");
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.zgjycebbf {
  stop-color: var(--svg-color--ff6e34, #FF6E34);
}

</style>
