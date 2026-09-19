<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inIgt9d)"><path class="jtq5yvb4h"/></g><g filter="url(#ieQsdjc)"><path stroke="url(#imJxWQb)" class="tvmdpsxgz"/></g><path fill="url(#izrJNLK)" class="r43ardy0p"/><g filter="url(#iVpVVHv)"><path class="ukun0zr2w"/></g><path fill="url(#iDk8M4b)" class="syui_3c1e"/><path fill="url(#iqhAKHM)" class="syui_3c1e"/><path fill="url(#ia84Ord)" class="ej3erkgif"/><g filter="url(#iEgzhld)"><path class="o4cae1ltj"/><path fill="url(#iGhc6hd)" class="g8yxf5b0p"/><path fill="url(#iPrKbZZ)" class="g8yxf5b0p"/></g><g filter="url(#iSNQiid)"><path class="qvtw3_t5d"/><path fill="url(#iMMpeQw)" class="oledkbbaw"/><path fill="url(#iNNBhia)" class="oledkbbaw"/></g><path fill="url(#iy9wexd)" transform="scale(-1 1)rotate(-14.867 27.08 74.13)" class="ofkpelbcu"/><path fill="url(#imsvv5c)" transform="scale(-1 1)rotate(-14.867 27.08 74.13)" class="ofkpelbcu"/><path fill="url(#iZCT3re)" transform="scale(-1 1)rotate(-14.867 27.08 74.13)" class="ofkpelbcu"/><path fill="url(#itIClMe)" class="m53_03cvw"/><path fill="url(#i6W8Ncb)" class="m53_03cvw"/><path fill="url(#iKrR2sb)" class="m53_03cvw"/><path fill="url(#iqxBuqb)" class="yihvobc3s"/><path fill="url(#iKLujkd)" class="yihvobc3s"/><g filter="url(#i6gUhzb)"><path fill="url(#iriMBde)" class="ulnh2gbeq"/><path fill="url(#iSqk5eb)" class="ulnh2gbeq"/><path fill="url(#i7yX83d)" class="ulnh2gbeq"/><path fill="url(#i0aGnie)" class="ulnh2gbeq"/></g><g filter="url(#iwqp55d)"><path fill="url(#iuAfIoh)" class="qyjlr9bhz"/><path fill="url(#inEZlgd)" class="qyjlr9bhz"/><path fill="url(#i5D31gb)" class="qyjlr9bhz"/></g><path fill="url(#iEm13rB)" class="xmz1p-bxa"/><path fill="url(#iW8Ytme)" class="xmz1p-bxa"/><path fill="url(#ix7odFc)" class="xmz1p-bxa"/><path clip-rule="evenodd" class="ycat-rbnu"/><g filter="url(#iEigrZL)"><path clip-rule="evenodd" class="rjzt55b2q"/></g><path class="h-dycq2ze"/><path fill="url(#iF3TrDe)" class="ad3hwtbmq"/><path fill="url(#i7vSGgd)" class="ccjii0bjm"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -26.252 -40.307)" class="m1l7k9jve"/><g filter="url(#i3PCQ4b)"><path class="sj50j-ygr"/><path fill="url(#iEibkGd)" class="y19y8w5ub"/></g><g filter="url(#iP4qige)"><path class="lxc7t245p"/></g><g filter="url(#iLRgt3b)"><path class="o6g259byy"/></g><path fill="url(#ijeQKkd)" class="nw3j99sey"/><path fill="url(#iXQSMxb)" class="nw3j99sey"/><path fill="url(#i5iySXc)" class="nw3j99sey"/><path fill="url(#iLP4tPd)" class="nw3j99sey"/><g filter="url(#is0ejfc)"><path fill="url(#ilNxuUb)" class="garbodb5m"/></g><g filter="url(#iRh06Bj)"><path fill="url(#icsvNNd)" class="jv239dbcz"/></g><defs><radialGradient id="imJxWQb" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.039 9.649)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="izrJNLK" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.776 20.233)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="iqhAKHM" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 19.151 17.904)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="ia84Ord" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.558 18.014)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iy9wexd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80955 4.93989 .09 1.583)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="cb_1-p-qf"/><stop offset="1" class="zr3rqsbal"/></radialGradient><radialGradient id="imsvv5c" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 .923 .84)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="r7mvh1bxd"/><stop offset="1" class="oz-5xeb0l"/></radialGradient><radialGradient id="itIClMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 14.323 13.53)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="zgjycebbf"/><stop offset=".849" class="cic7ureox"/></radialGradient><radialGradient id="i6W8Ncb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03122 3.14064 -3.13218 2.02576 14.76 11.655)" gradientUnits="userSpaceOnUse"><stop class="pyqlo9ccb"/><stop offset="1" class="tim0t4m8u"/></radialGradient><radialGradient id="iKrR2sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.838 15.278)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="xu4oisaxz"/><stop offset="1" class="jtmbyac_e"/></radialGradient><radialGradient id="iqxBuqb" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 9.116 6.743)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="rcpmccbyc"/><stop offset=".684" class="wdglv_bwm"/></radialGradient><radialGradient id="iKLujkd" cx="0" cy="0" r="1" gradientTransform="matrix(.12006 -.29152 .4375 .18019 19.938 8.653)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iSqk5eb" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.681 7.634)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="i7yX83d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 19.578 8.821)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="nkfrpdbdq"/><stop offset="1" class="eqwiy2pxg"/></radialGradient><radialGradient id="i0aGnie" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 18.75 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="iuAfIoh" cx="0" cy="0" r="1" gradientTransform="rotate(-141.435 9.956 .265)scale(3.12459 4.73465)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="te4zz7dbn"/><stop offset="1" class="otf1z2b9l"/></radialGradient><radialGradient id="inEZlgd" cx="0" cy="0" r="1" gradientTransform="rotate(-144.319 10.77 -.616)scale(1.50012 2.40215)" gradientUnits="userSpaceOnUse"><stop class="r-95cxbic"/><stop offset="1" class="efo8wovhu"/></radialGradient><radialGradient id="i5D31gb" cx="0" cy="0" r="1" gradientTransform="matrix(.53132 .14843 -.072 .25775 14.97 8.509)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="cl2mrcsll"/><stop offset="1" class="hms2sfnpk"/></radialGradient><radialGradient id="iEm13rB" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 9.034 2.55)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="iW8Ytme" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 5.501 10.62)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="iF3TrDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.045 7.708)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i7vSGgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.213 7.73)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iEibkGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.34375 -.8049 -.04293 15.651 15.274)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="fs54pab_v"/><stop offset="1" class="zm5b18b9s"/></radialGradient><radialGradient id="ijeQKkd" cx="0" cy="0" r="1" gradientTransform="rotate(-87.255 16.584 -1.3)scale(4.56774 2.32974)" gradientUnits="userSpaceOnUse"><stop class="q-nbb5ezw"/><stop offset="1" class="jqsx2jbza"/></radialGradient><radialGradient id="iXQSMxb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 1.32812 -1.6478 1.08562 15.432 11.389)" gradientUnits="userSpaceOnUse"><stop class="eq7ur_bkf"/><stop offset="1" class="uverm5y1q"/></radialGradient><linearGradient id="iDk8M4b" x1="15.214" x2="15.214" y1="17.811" y2="18.342" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iGhc6hd" x1="20.089" x2="21.073" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="iPrKbZZ" x1="21.526" x2="21.526" y1="27.94" y2="27.569" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iMMpeQw" x1="11.064" x2="10.378" y1="25.029" y2="25.694" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="iNNBhia" x1="8.917" x2="9.132" y1="26.233" y2="26.405" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iZCT3re" x1="-.003" x2=".233" y1="1.875" y2="1.869" gradientUnits="userSpaceOnUse"><stop class="ayx8pzyyv"/><stop offset="1" class="r1mf-bcbj"/></linearGradient><linearGradient id="iriMBde" x1="16.994" x2="19.856" y1="8.376" y2="8.548" gradientUnits="userSpaceOnUse"><stop class="w6b0chbuk"/><stop offset="1" class="n3dqqoxxk"/></linearGradient><linearGradient id="ix7odFc" x1="17.053" x2="16.904" y1="7.585" y2="7.597" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="i5iySXc" x1="15.886" x2="15.979" y1="15.498" y2="14.248" gradientUnits="userSpaceOnUse"><stop class="ky5pzdbbm"/><stop offset="1" class="giu-ixb2s"/></linearGradient><linearGradient id="iLP4tPd" x1="18.245" x2="17.393" y1="15.209" y2="15.209" gradientUnits="userSpaceOnUse"><stop class="uk2nrwb0k"/><stop offset="1" class="uy34yibrn"/></linearGradient><linearGradient id="ilNxuUb" x1="21.694" x2="15.214" y1="24.826" y2="18.889" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="icsvNNd" x1="15.5" x2="15.756" y1="7.036" y2="4.114" gradientUnits="userSpaceOnUse"><stop offset=".421" class="esqjgpxir"/><stop offset="1" class="lj6qdgbam"/></linearGradient><filter id="inIgt9d" width="7.28" height="8.609" x="10.996" y="19.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2184" result="effect2_innerShadow_2_2184"/></filter><filter id="ieQsdjc" width="5.734" height="7.279" x="11.071" y="20.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2184" stdDeviation=".25"/></filter><filter id="iVpVVHv" width="11.64" height="10.135" x="13.28" y="17.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/></filter><filter id="iEgzhld" width="4.352" height="2.364" x="20.218" y="25.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/></filter><filter id="iSNQiid" width="3.579" height="3.542" x="7.83" y="24.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/></filter><filter id="i6gUhzb" width="4.443" height="5.249" x="15.413" y="5.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.521569 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/></filter><filter id="iwqp55d" width="5.586" height="5.499" x="14.291" y="3.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.682353 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/></filter><filter id="iEigrZL" width="1.013" height=".568" x="18.181" y="6.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/></filter><filter id="i3PCQ4b" width="6.876" height="3.179" x="15.419" y="14.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.607843 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.501961 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2184" result="effect2_innerShadow_2_2184"/></filter><filter id="iP4qige" width="1.171" height="1.439" x="21.358" y="17.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.545098 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/></filter><filter id="iLRgt3b" width="1.196" height="1.065" x="20.878" y="17.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.54902 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2184"/></filter><filter id="is0ejfc" width="8.168" height="8.42" x="14.276" y="18.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2184" stdDeviation=".375"/></filter><filter id="iRh06Bj" width="2.276" height="3.492" x="14.545" y="4.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2184" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-kneeling-facing-right-medium-light" /></template>
<style>
.ad3hwtbmq {
  d: path("M18.717 7.73v-.004c0-.32.137-.58.306-.58c.17 0 .307.26.307.58v.003z");
}

.ayx8pzyyv {
  stop-color: var(--svg-color--d59984, #D59984);
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.cb_1-p-qf {
  stop-color: var(--svg-color--d08a75, #D08A75);
}

.ccjii0bjm {
  d: path("m18.912 7.73l-.004-.073c0-.185.079-.336.176-.336s.175.15.175.336l-.004.072z");
}

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cic7ureox {
  stop-color: var(--svg-color--e54d24, #E54D24);
}

.cl2mrcsll {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.efo8wovhu {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
  stop-opacity: 0;
}

.ej3erkgif {
  d: path("M20.293 20.52v-.002c-1.787.442-3.937.808-5.747.261c-1.2-.362-1.266-1.816-1.266-2.875l7.61.079q.4.138.701.336z");
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.eq7ur_bkf {
  stop-color: var(--svg-color--ff9337, #FF9337);
}

.eqwiy2pxg {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
  stop-opacity: 0;
}

.esqjgpxir {
  stop-color: var(--svg-color--fff9bd, #FFF9BD);
}

.fs54pab_v {
  stop-color: var(--svg-color--e4ad98, #E4AD98);
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

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
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

.hms2sfnpk {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
  stop-opacity: 0;
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
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

.jv239dbcz {
  d: path("M16.163 6.01a13 13 0 0 0-.63 1.412a2.9 2.9 0 0 1-.458-2.038c.07-.496.738-.6 1.087-.24c.252.26.168.545 0 .866");
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.ksl77bchk {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
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

.lj6qdgbam {
  stop-color: var(--svg-color--fff9bd, #FFF9BD);
  stop-opacity: 0;
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.lxc7t245p {
  fill: var(--svg-color--ce9982, #CE9982);
  d: path("m21.401 17.147l-.043.633c.233.181.452.427.603.608a.27.27 0 0 0 .346.058a.243.243 0 0 0 .085-.338a3.6 3.6 0 0 0-.99-.961");
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

.n3dqqoxxk {
  stop-color: var(--svg-color--f2b592, #F2B592);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nkfrpdbdq {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.nw3j99sey {
  d: path("M17.724 12.612a1.261 1.261 0 0 0-2.519-.119l-.155 2.775l2.566.152z");
}

.o4cae1ltj {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M20.23 26.517a6.3 6.3 0 0 1 1.413-.642l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.o6g259byy {
  fill: var(--svg-color--cd9789, #CD9789);
  d: path("M21.448 17.744c-.325-.003-.516.179-.57.27c.271.144.499.376.65.567c.1.124.278.169.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.533");
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

.otf1z2b9l {
  stop-color: var(--svg-color--ffedae, #FFEDAE);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.oz-5xeb0l {
  stop-color: var(--svg-color--ce9074, #CE9074);
  stop-opacity: 0;
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
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

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qvtw3_t5d {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m10.524 24.764l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.179 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.qyjlr9bhz {
  d: path("M19.767 4.593c-.237-.487-.796-.603-1.074-.588c-.86.047-.977.344-1.754.184c-.821-.17-1.226-.121-1.578.039l-.007.003c-.346.157-1.063.483-1.063 1.95c0 1.351.482 2.065.715 2.32l-.046.017c-.232.083-.327.33-.244.561c.072.198.322.311.637.262c.36-.057.625-.106.832-.147a.25.25 0 0 0 .2-.244V7.837c0-.469.33-.749.476-.832c.016-.484.164-.707.406-.824c.401-.194.526-.098 1.485-.157c1.015-.061 1.312-.821 1.015-1.43");
}

.r-95cxbic {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
}

.r1mf-bcbj {
  stop-color: var(--svg-color--d59984, #D59984);
  stop-opacity: 0;
}

.r43ardy0p {
  d: path("M17.27 25.616c.05-1.838-.196-4.493-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.265c-1.062-.265-2.578-.171-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.141 2.372.086 2.43-2.046");
}

.r7mvh1bxd {
  stop-color: var(--svg-color--ce9074, #CE9074);
}

.rcpmccbyc {
  stop-color: var(--svg-color--fec19d, #FEC19D);
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.rjzt55b2q {
  fill: var(--svg-color--915d37, #915D37);
  fill-rule: evenodd;
  d: path("M18.81 6.697a.8.8 0 0 1 .216-.016a.15.15 0 0 0 .037-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.408.173a.15.15 0 0 0 .178.24c.085-.062.19-.1.29-.12");
}

.sj50j-ygr {
  fill: var(--svg-color--d8a490, #D8A490);
  d: path("m17.315 16.076l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.984c.266.391.765.859 2.2.946c1.03.062 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
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

.te4zz7dbn {
  stop-color: var(--svg-color--ffe2ad, #FFE2AD);
}

.tim0t4m8u {
  stop-color: var(--svg-color--ff953a, #FF953A);
  stop-opacity: 0;
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

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.w6b0chbuk {
  stop-color: var(--svg-color--dfa289, #DFA289);
}

.wdglv_bwm {
  stop-color: var(--svg-color--f2b08a, #F2B08A);
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

.y19y8w5ub {
  d: path("m17.315 16.076l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.984c.266.391.765.859 2.2.946c1.03.062 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
}

.ycat-rbnu {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M18.577 8.843a.125.125 0 0 0 .001.177c.238.234.583.293.692.305a.125.125 0 1 0 .026-.25c-.094-.009-.367-.061-.543-.234a.125.125 0 0 0-.177.002");
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.yihvobc3s {
  d: path("M20.052 7.9a1 1 0 0 1-.258-.458h-.18v1.125c.215.137.523.116.614-.09c.078-.175.02-.394-.176-.578");
}

.zgjycebbf {
  stop-color: var(--svg-color--ff6e34, #FF6E34);
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zm5b18b9s {
  stop-color: var(--svg-color--e4ad98, #E4AD98);
  stop-opacity: 0;
}

.zr3rqsbal {
  stop-color: var(--svg-color--e5ab92, #E5AB92);
}

</style>
