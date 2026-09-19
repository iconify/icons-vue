<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQ9MXKi)"><path class="ao1jy03ok"/></g><g filter="url(#ifPZCze)"><path stroke="url(#inH7SIb)" class="nhpz1ukdc"/></g><path fill="url(#iTfv37b)" class="dxj6ueb5g"/><g filter="url(#iMeFTed)"><path class="ur39p8y2b"/></g><path fill="url(#iFYLNte)" class="v3e60lbxs"/><path fill="url(#iG1kIwb)" class="v3e60lbxs"/><path fill="url(#iLMd4La)" class="oy0sdhk3a"/><g filter="url(#iupRrCe)"><path class="b1kejtblj"/><path fill="url(#iF3kREz)" class="ty__8ybpi"/><path fill="url(#idTNDed)" class="ty__8ybpi"/></g><g filter="url(#iLBzL8c)"><path class="egmvf7wfc"/><path fill="url(#ijCIrUc)" class="mmevalcjp"/><path fill="url(#ioxxpNd)" class="mmevalcjp"/></g><path fill="url(#iXuxDie)" transform="rotate(-14.867 13.886 9.43)" class="f7-sz_buv"/><path fill="url(#i2xfvze)" transform="rotate(-14.867 13.886 9.43)" class="f7-sz_buv"/><path fill="url(#iwKjSLb)" transform="rotate(-14.867 13.886 9.43)" class="f7-sz_buv"/><path fill="url(#ihbHyyc)" class="dnobedcnj"/><path fill="url(#i5u87fe)" class="dnobedcnj"/><path fill="url(#ioWdqPe)" class="dnobedcnj"/><path fill="url(#iIA8AMb)" class="ns0yj4b3t"/><path fill="url(#i4CI4ye)" class="ns0yj4b3t"/><g filter="url(#i60V9Ie)"><path fill="url(#iKiJ7Ud)" class="jyxas_bip"/><path fill="url(#ifDuZDc)" class="jyxas_bip"/><path fill="url(#iDd0b1b)" class="jyxas_bip"/><path fill="url(#ildiQxt)" class="jyxas_bip"/></g><g filter="url(#if9U8Jd)"><path fill="url(#iguauSc)" class="pcbk2pgws"/><path fill="url(#iUXt6ec)" class="pcbk2pgws"/><path fill="url(#i689Nwb)" class="pcbk2pgws"/><path fill="url(#ijn26Ab)" class="pcbk2pgws"/></g><path fill="url(#ictiBOg)" class="tzj-vacfb"/><path fill="url(#iEqJDXd)" class="tzj-vacfb"/><path fill="url(#i6mXQmd)" class="tzj-vacfb"/><path clip-rule="evenodd" class="dacx6qbei"/><g filter="url(#i2tesqe)"><path clip-rule="evenodd" class="c7r2hsbrp"/></g><path class="po14_5esb"/><path fill="url(#iu04uHx)" class="nq6fljbdw"/><path fill="url(#izKyi7b)" class="uym829oaa"/><ellipse fill="url(#iXgsRne)" transform="rotate(24.61 12.852 7.378)" class="ovu88ccyb"/><g filter="url(#iZwxmpb)"><path class="b4i_uhb-g"/><path fill="url(#iu12B4a)" class="qsczywo1x"/></g><g filter="url(#i3lw3fe)"><path class="a-zz-fb-x"/></g><g filter="url(#iq4MkRz)"><path class="ov2v5kzqd"/></g><path fill="url(#iytwIwb)" class="nscm5u7qs"/><path fill="url(#iFsLamd)" class="nscm5u7qs"/><path fill="url(#iQXkWfo)" class="nscm5u7qs"/><path fill="url(#i3Ic41b)" class="nscm5u7qs"/><g filter="url(#inMJA2c)"><path fill="url(#i9YQGId)" class="e2t1tbbys"/></g><g filter="url(#inwJZ3b)"><path fill="url(#iV9J53b)" class="y4lvhkb3a"/></g><defs><radialGradient id="inH7SIb" cx="0" cy="0" r="1" gradientTransform="matrix(3.48437 -4.05522 3.01176 2.5878 16.13 26.585)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iTfv37b" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 3.29646 -1.78135 -.28708 16.224 20.234)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="iG1kIwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 12.849 17.904)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iLMd4La" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 3.14063 -8.2876 -.28863 14.443 18.014)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iXuxDie" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80956 4.93988 13.977 11.012)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nov_osbjm"/><stop offset="1" class="b10rjxgth"/></radialGradient><radialGradient id="i2xfvze" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 5.025 9.739)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="zuv46pbeh"/><stop offset="1" class="a0cytj3vs"/></radialGradient><radialGradient id="ihbHyyc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4531 4.00002 -4.9949 -4.31194 17.677 13.53)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="zgjycebbf"/><stop offset=".849" class="cic7ureox"/></radialGradient><radialGradient id="i5u87fe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03122 3.14064 -3.13218 -2.02576 17.24 11.655)" gradientUnits="userSpaceOnUse"><stop class="pyqlo9ccb"/><stop offset="1" class="tim0t4m8u"/></radialGradient><radialGradient id="ioWdqPe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73437 .23436 -.4261 -6.78981 17.162 15.28)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="xu4oisaxz"/><stop offset="1" class="jtmbyac_e"/></radialGradient><radialGradient id="iIA8AMb" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 .25781 -.36391 .67269 11.657 8.337)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="i4CI4ye" cx="0" cy="0" r="1" gradientTransform="matrix(-.12005 -.29152 .43751 -.18018 12.063 8.654)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="ifDuZDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 15.319 7.634)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="iDd0b1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 12.422 8.821)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="ildiQxt" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 13.25 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="iguauSc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4431 -1.9479 2.95162 3.702 14.424 6.678)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="iUXt6ec" cx="0" cy="0" r="1" gradientTransform="matrix(1.21851 -.87498 1.40111 1.9512 12.123 5.165)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="i689Nwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53132 .14843 -.072 -.25775 17.03 8.508)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="ijn26Ab" cx="0" cy="0" r="1" gradientTransform="matrix(.90403 -.21096 .55771 2.39 15.064 7.025)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="ictiBOg" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.21094 .10296 .35463 15.002 7.517)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iEqJDXd" cx="0" cy="0" r="1" gradientTransform="matrix(.22596 1.17975 -1.22934 .23546 15.033 7.216)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="iu04uHx" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.955 7.708)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="izKyi7b" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.787 7.73)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iu12B4a" cx="0" cy="0" r="1" gradientTransform="rotate(86.947 .12 16.26)scale(2.34708 .80604)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="tr08sbvmm"/><stop offset="1" class="fz8d0bv0m"/></radialGradient><radialGradient id="iytwIwb" cx="0" cy="0" r="1" gradientTransform="rotate(-92.745 14.76 .557)scale(4.56774 2.32974)" gradientUnits="userSpaceOnUse"><stop class="q-nbb5ezw"/><stop offset="1" class="jqsx2jbza"/></radialGradient><radialGradient id="iFsLamd" cx="0" cy="0" r="1" gradientTransform="rotate(123.378 5.216 10.157)scale(1.59045 1.97328)" gradientUnits="userSpaceOnUse"><stop class="eq7ur_bkf"/><stop offset="1" class="uverm5y1q"/></radialGradient><linearGradient id="iFYLNte" x1="16.786" x2="16.786" y1="17.811" y2="18.342" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iF3kREz" x1="11.911" x2="10.927" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="idTNDed" x1="10.474" x2="10.474" y1="27.94" y2="27.569" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="ijCIrUc" x1="20.936" x2="21.622" y1="25.029" y2="25.694" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="ioxxpNd" x1="23.083" x2="22.868" y1="26.233" y2="26.405" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iwKjSLb" x1="13.883" x2="14.119" y1="11.305" y2="11.299" gradientUnits="userSpaceOnUse"><stop class="b3gb996av"/><stop offset="1" class="crjyhppor"/></linearGradient><linearGradient id="iKiJ7Ud" x1="15.006" x2="12.144" y1="8.376" y2="8.548" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="i6mXQmd" x1="14.947" x2="15.095" y1="7.585" y2="7.597" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="iXgsRne" x1="12.781" x2="12.967" y1="7.34" y2="7.4" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iQXkWfo" x1="16.114" x2="16.021" y1="15.498" y2="14.248" gradientUnits="userSpaceOnUse"><stop class="ky5pzdbbm"/><stop offset="1" class="giu-ixb2s"/></linearGradient><linearGradient id="i3Ic41b" x1="13.755" x2="14.607" y1="15.209" y2="15.209" gradientUnits="userSpaceOnUse"><stop class="uk2nrwb0k"/><stop offset="1" class="uy34yibrn"/></linearGradient><linearGradient id="i9YQGId" x1="10.306" x2="16.786" y1="24.826" y2="18.889" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="iV9J53b" x1="16.5" x2="16.244" y1="7.036" y2="4.114" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><filter id="iQ9MXKi" width="7.28" height="8.609" x="14.724" y="19.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_255" result="effect2_innerShadow_4002_255"/></filter><filter id="ifPZCze" width="5.734" height="7.279" x="15.195" y="20.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_255" stdDeviation=".25"/></filter><filter id="iMeFTed" width="11.64" height="10.135" x="7.83" y="17.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/></filter><filter id="iupRrCe" width="4.352" height="2.364" x="7.83" y="25.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/></filter><filter id="iLBzL8c" width="3.579" height="3.542" x="20.591" y="24.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/></filter><filter id="i60V9Ie" width="4.443" height="5.249" x="11.944" y="5.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.611765 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/></filter><filter id="if9U8Jd" width="5.586" height="5.499" x="12.123" y="3.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/></filter><filter id="i2tesqe" width="1.013" height=".568" x="12.705" y="6.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/></filter><filter id="iZwxmpb" width="6.876" height="3.179" x="9.905" y="14.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.678431 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.537255 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_255" result="effect2_innerShadow_4002_255"/></filter><filter id="i3lw3fe" width="1.071" height="1.439" x="9.571" y="17.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.623529 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/></filter><filter id="iq4MkRz" width="1.196" height="1.065" x="9.926" y="17.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.623529 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_255"/></filter><filter id="inMJA2c" width="8.168" height="8.42" x="9.556" y="18.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_255" stdDeviation=".375"/></filter><filter id="inwJZ3b" width="2.276" height="3.492" x="15.179" y="4.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_255" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-kneeling-light" /></template>
<style>
.a-zz-fb-x {
  fill: var(--svg-color--dda89d, #DDA89D);
  d: path("m10.599 17.147l.043.633a4.3 4.3 0 0 0-.603.608a.27.27 0 0 1-.346.058a.243.243 0 0 1-.085-.338c.312-.472.795-.844.99-.961");
}

.a0cytj3vs {
  stop-color: var(--svg-color--d49c8a, #D49C8A);
  stop-opacity: 0;
}

.ao1jy03ok {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M14.73 25.616c-.05-1.838.196-4.493.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.265c1.062-.265 2.578-.171 3.765-.117l.39 1.516c-1.233.125-3.339.522-3.843.648c-.562.141-2.371.086-2.43-2.046");
}

.b10rjxgth {
  stop-color: var(--svg-color--f5c1ab, #F5C1AB);
}

.b1kejtblj {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M11.77 26.517a6.3 6.3 0 0 0-1.413-.642l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.b3gb996av {
  stop-color: var(--svg-color--ecac9a, #ECAC9A);
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.b4i_uhb-g {
  fill: var(--svg-color--e6b3a6, #E6B3A6);
  d: path("m14.685 16.076l-.04-.78l1.891-.126c.047.664.118 1.594-.148 1.984c-.266.391-.765.859-2.2.946a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.039-.192.39-.568.79-.711c1.254-.45 2.96-.82 3.988-.95");
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.c7r2hsbrp {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M13.19 6.697a.8.8 0 0 0-.216-.016a.15.15 0 0 1-.037-.298c.07-.008.187-.006.313.02c.127.025.277.076.408.173a.15.15 0 0 1-.178.24a.7.7 0 0 0-.29-.12");
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.cic7ureox {
  stop-color: var(--svg-color--e54d24, #E54D24);
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.crjyhppor {
  stop-color: var(--svg-color--ecac9a, #ECAC9A);
  stop-opacity: 0;
}

.dacx6qbei {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.424 8.843a.125.125 0 0 1-.002.177c-.238.234-.583.293-.692.305a.125.125 0 1 1-.026-.25c.094-.009.367-.061.543-.234a.125.125 0 0 1 .177.002");
}

.dnobedcnj {
  d: path("M13.677 13.127c-.162 1.15-.094 2.637.016 3.528v1.289h5.031c-.055-2.063-.578-4.729-1.367-6.047c-.664-1.11-1.422-1.176-2.055-.957c-.605.183-1.422.75-1.625 2.187");
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxj6ueb5g {
  d: path("M14.73 25.616c-.05-1.838.196-4.493.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.265c1.062-.265 2.578-.171 3.765-.117l.39 1.516c-1.233.125-3.339.522-3.843.648c-.562.141-2.371.086-2.43-2.046");
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e2t1tbbys {
  d: path("m10.318 20.444l.656 5.492l.312.125l-.43-5.73a.487.487 0 0 1 .482-.528c.926-.006 3.848 0 4.542 0c.812 0 1.094-.273 1.094-.648c-1.193-.01-4.677-.025-5.664 0s-1.04.861-.992 1.289");
}

.egmvf7wfc {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m21.476 24.764l-.885.75l.406 1.5c.39.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.179 0-.257l-2.285-2.769a.25.25 0 0 0-.355-.031");
}

.eq7ur_bkf {
  stop-color: var(--svg-color--ff9337, #FF9337);
}

.f7-sz_buv {
  d: path("M13.886 9.429h1.976v2.198h-1.976z");
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

.fz8d0bv0m {
  stop-color: var(--svg-color--f8c0b0, #F8C0B0);
  stop-opacity: 0;
}

.giu-ixb2s {
  stop-color: var(--svg-color--ef6623, #EF6623);
  stop-opacity: 0;
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
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

.jyxas_bip {
  d: path("M12.172 6.936c.038-.802.298-1.188.42-1.3h3.732l.063 3.163c-.867 2.122-3.512 2.213-3.907 1.445c-.395-.767-.353-2.38-.308-3.308");
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
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

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.mmevalcjp {
  d: path("m21.476 24.764l-.885.75l.406 1.5c.39.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.179 0-.257l-2.285-2.769a.25.25 0 0 0-.355-.031");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nhpz1ukdc {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.208 20.592c-.138.941-.573 3.263-1.239 5.338a.5.5 0 0 0 .152.535a.55.55 0 0 0 .538.085c.689-.243 2.053-.526 3.737-.302");
}

.nov_osbjm {
  stop-color: var(--svg-color--e19d8a, #E19D8A);
}

.nq6fljbdw {
  d: path("M13.283 7.73v-.004c0-.32-.137-.58-.306-.58c-.17 0-.307.26-.307.58v.003z");
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.ns0yj4b3t {
  d: path("M11.948 7.9c.156-.147.237-.366.258-.458h.18v1.125c-.215.137-.523.116-.614-.09c-.078-.175-.02-.394.176-.578");
}

.nscm5u7qs {
  d: path("M14.276 12.612a1.261 1.261 0 0 1 2.519-.119l.155 2.775l-2.566.152z");
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.ov2v5kzqd {
  fill: var(--svg-color--dda89d, #DDA89D);
  d: path("M10.552 17.744c.325-.003.516.179.57.27a2.2 2.2 0 0 0-.65.567c-.1.124-.278.169-.413.086a.266.266 0 0 1-.079-.39c.257-.329.48-.49.572-.533");
}

.ovu88ccyb {
  cx: 12.852px;
  cy: 7.378px;
  rx: 0.064px;
  ry: 0.088px;
}

.oy0sdhk3a {
  d: path("M11.707 20.52v-.002c1.787.442 3.938.808 5.747.261c1.2-.362 1.266-1.816 1.266-2.875l-7.61.079a3.2 3.2 0 0 0-.701.336z");
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.pcbk2pgws {
  d: path("M12.233 4.593c.237-.487.796-.603 1.074-.588c.86.047.976.344 1.754.184c.821-.17 1.227-.121 1.578.039l.007.003c.346.157 1.063.483 1.063 1.95c0 1.351-.482 2.065-.715 2.32l.046.017c.232.083.327.33.244.561c-.072.198-.322.311-.637.262c-.36-.057-.625-.106-.832-.147a.25.25 0 0 1-.2-.244V7.837a.99.99 0 0 0-.476-.832c-.016-.484-.164-.707-.406-.824c-.401-.194-.526-.098-1.485-.157c-1.015-.061-1.312-.821-1.015-1.43");
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.po14_5esb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.678 7.73h.988c0-.392-.221-.71-.494-.71s-.494.318-.494.71");
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

.qsczywo1x {
  d: path("m14.685 16.076l-.04-.78l1.891-.126c.047.664.118 1.594-.148 1.984c-.266.391-.765.859-2.2.946a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.039-.192.39-.568.79-.711c1.254-.45 2.96-.82 3.988-.95");
}

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.tim0t4m8u {
  stop-color: var(--svg-color--ff953a, #FF953A);
  stop-opacity: 0;
}

.tr08sbvmm {
  stop-color: var(--svg-color--f8c0b0, #F8C0B0);
}

.ty__8ybpi {
  d: path("M11.77 26.517a6.3 6.3 0 0 0-1.413-.642l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.tzj-vacfb {
  d: path("m14.85 8.39l.2-1.44a.727.727 0 0 1-.2 1.44");
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uk2nrwb0k {
  stop-color: var(--svg-color--d36030, #D36030);
}

.ur39p8y2b {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M9.236 21.108c.137.575.807 3.427 1.125 4.78c-.573.233-1.39.67-2.067 1.009c-.324.162-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.17c1.787.443 3.937.81 5.747.262c1.2-.362 1.266-1.816 1.266-2.875l-7.61.079a2.726 2.726 0 0 0-1.874 3.125");
}

.uverm5y1q {
  stop-color: var(--svg-color--ff9337, #FF9337);
  stop-opacity: 0;
}

.uy34yibrn {
  stop-color: var(--svg-color--d36030, #D36030);
  stop-opacity: 0;
}

.uym829oaa {
  d: path("m13.088 7.73l.004-.073c0-.185-.079-.336-.176-.336s-.175.15-.175.336q-.001.038.004.072z");
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.v3e60lbxs {
  d: path("M9.236 21.108c.137.575.807 3.427 1.125 4.78c-.573.233-1.39.67-2.067 1.009c-.324.162-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.17c1.787.443 3.937.81 5.747.262c1.2-.362 1.266-1.816 1.266-2.875l-7.61.079a2.726 2.726 0 0 0-1.874 3.125");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xu4oisaxz {
  stop-color: var(--svg-color--cd5a3b, #CD5A3B);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.y4lvhkb3a {
  d: path("M15.837 6.01c.302.58.535 1.15.63 1.412c.476-.71.54-1.457.458-2.038c-.07-.496-.738-.6-1.087-.24c-.252.26-.168.545 0 .866");
}

.zgjycebbf {
  stop-color: var(--svg-color--ff6e34, #FF6E34);
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zuv46pbeh {
  stop-color: var(--svg-color--d49c8a, #D49C8A);
}

</style>
