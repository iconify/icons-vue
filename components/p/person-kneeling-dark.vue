<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZfKKYb)"><path class="ao1jy03ok"/></g><g filter="url(#i6eLO5d)"><path stroke="url(#inH7SIb)" class="nhpz1ukdc"/></g><path fill="url(#iTfv37b)" class="dxj6ueb5g"/><g filter="url(#i38ZE0b)"><path class="ur39p8y2b"/></g><path fill="url(#iFYLNte)" class="v3e60lbxs"/><path fill="url(#iG1kIwb)" class="v3e60lbxs"/><path fill="url(#iLMd4La)" class="oy0sdhk3a"/><g filter="url(#iDGM5Rd)"><path class="b1kejtblj"/><path fill="url(#iF3kREz)" class="ty__8ybpi"/><path fill="url(#idTNDed)" class="ty__8ybpi"/></g><g filter="url(#iNsutqZ)"><path class="egmvf7wfc"/><path fill="url(#ijCIrUc)" class="mmevalcjp"/><path fill="url(#ioxxpNd)" class="mmevalcjp"/></g><path fill="url(#iHV4cPb)" transform="rotate(-14.867 13.886 9.43)" class="f7-sz_buv"/><path fill="url(#iydchQe)" transform="rotate(-14.867 13.886 9.43)" class="f7-sz_buv"/><path fill="url(#i9oB2vb)" transform="rotate(-14.867 13.886 9.43)" class="f7-sz_buv"/><path fill="url(#ihbHyyc)" class="dnobedcnj"/><path fill="url(#i5u87fe)" class="dnobedcnj"/><path fill="url(#ioWdqPe)" class="dnobedcnj"/><path fill="url(#ifjTILc)" class="ns0yj4b3t"/><g filter="url(#i4BqQsb)"><path fill="url(#iDkGm9d)" class="jyxas_bip"/><path fill="url(#iu1ds9b)" class="jyxas_bip"/><path fill="url(#iKdxtNc)" class="jyxas_bip"/><path fill="url(#ikarOpe)" class="jyxas_bip"/></g><g filter="url(#iR4nwce)"><path fill="url(#iguauSc)" class="pcbk2pgws"/><path fill="url(#iUXt6ec)" class="pcbk2pgws"/><path fill="url(#i689Nwb)" class="pcbk2pgws"/><path fill="url(#ijn26Ab)" class="pcbk2pgws"/></g><path fill="url(#i9u19Qc)" class="tzj-vacfb"/><path fill="url(#icz1zvE)" class="tzj-vacfb"/><path clip-rule="evenodd" class="xky7n8z-u"/><g filter="url(#iQzsDBb)"><path clip-rule="evenodd" class="l40jxvb0l"/></g><path class="po14_5esb"/><path fill="url(#iu04uHx)" class="nq6fljbdw"/><path fill="url(#izKyi7b)" class="uym829oaa"/><ellipse fill="url(#iNhEkpd)" transform="rotate(24.61 12.852 7.378)" class="ovu88ccyb"/><g filter="url(#iE6vAEe)"><path class="wk6z7-t0m"/><path fill="url(#i1DxAGd)" class="qsczywo1x"/></g><g filter="url(#iDgPRwd)"><path class="s75d29q8s"/></g><g filter="url(#igaStTd)"><path class="tp6928c8i"/></g><path fill="url(#iytwIwb)" class="nscm5u7qs"/><path fill="url(#iFsLamd)" class="nscm5u7qs"/><path fill="url(#iQXkWfo)" class="nscm5u7qs"/><path fill="url(#i3Ic41b)" class="nscm5u7qs"/><g filter="url(#iglaexC)"><path fill="url(#i9YQGId)" class="e2t1tbbys"/></g><g filter="url(#i3fDUlb)"><path fill="url(#ihomYBd)" class="um92ahxqy"/></g><defs><radialGradient id="inH7SIb" cx="0" cy="0" r="1" gradientTransform="matrix(3.48437 -4.05522 3.01176 2.5878 16.13 26.585)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iTfv37b" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 3.29646 -1.78135 -.28708 16.224 20.234)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="iG1kIwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 12.849 17.904)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iLMd4La" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 3.14063 -8.2876 -.28863 14.443 18.014)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iHV4cPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80956 4.93988 13.977 11.012)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="om366ybrp"/><stop offset="1" class="al52zb3wa"/></radialGradient><radialGradient id="iydchQe" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 5.025 9.739)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="numeh5b7w"/><stop offset="1" class="yqah6ebzx"/></radialGradient><radialGradient id="ihbHyyc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4531 4.00002 -4.9949 -4.31194 17.677 13.53)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="zgjycebbf"/><stop offset=".849" class="cic7ureox"/></radialGradient><radialGradient id="i5u87fe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03122 3.14064 -3.13218 -2.02576 17.24 11.655)" gradientUnits="userSpaceOnUse"><stop class="pyqlo9ccb"/><stop offset="1" class="tim0t4m8u"/></radialGradient><radialGradient id="ioWdqPe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73437 .23436 -.4261 -6.78981 17.162 15.28)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="xu4oisaxz"/><stop offset="1" class="jtmbyac_e"/></radialGradient><radialGradient id="ifjTILc" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 .25781 -.36391 .67269 11.657 8.337)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iu1ds9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 15.319 7.634)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iKdxtNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 12.422 8.821)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="ikarOpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 13.25 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="iguauSc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4431 -1.9479 2.95162 3.702 14.424 6.678)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="iUXt6ec" cx="0" cy="0" r="1" gradientTransform="matrix(1.21851 -.87498 1.40111 1.9512 12.123 5.165)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="i689Nwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53132 .14843 -.072 -.25775 17.03 8.508)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="ijn26Ab" cx="0" cy="0" r="1" gradientTransform="matrix(.90403 -.21096 .55771 2.39 15.064 7.025)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="i9u19Qc" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.21094 .10296 .35463 15.002 7.517)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="iu04uHx" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.955 7.708)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="izKyi7b" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.787 7.73)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="i1DxAGd" cx="0" cy="0" r="1" gradientTransform="rotate(86.947 .12 16.26)scale(2.34708 .80604)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="bm70d-gaq"/><stop offset="1" class="xojzxxboq"/></radialGradient><radialGradient id="iytwIwb" cx="0" cy="0" r="1" gradientTransform="rotate(-92.745 14.76 .557)scale(4.56774 2.32974)" gradientUnits="userSpaceOnUse"><stop class="q-nbb5ezw"/><stop offset="1" class="jqsx2jbza"/></radialGradient><radialGradient id="iFsLamd" cx="0" cy="0" r="1" gradientTransform="rotate(123.378 5.216 10.157)scale(1.59045 1.97328)" gradientUnits="userSpaceOnUse"><stop class="eq7ur_bkf"/><stop offset="1" class="uverm5y1q"/></radialGradient><linearGradient id="iFYLNte" x1="16.786" x2="16.786" y1="17.811" y2="18.342" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iF3kREz" x1="11.911" x2="10.927" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="idTNDed" x1="10.474" x2="10.474" y1="27.94" y2="27.569" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="ijCIrUc" x1="20.936" x2="21.622" y1="25.029" y2="25.694" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="ioxxpNd" x1="23.083" x2="22.868" y1="26.233" y2="26.405" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="i9oB2vb" x1="13.883" x2="14.119" y1="11.305" y2="11.299" gradientUnits="userSpaceOnUse"><stop class="ndh-ggbqf"/><stop offset="1" class="naoj9jbij"/></linearGradient><linearGradient id="iDkGm9d" x1="15.006" x2="12.144" y1="8.376" y2="8.548" gradientUnits="userSpaceOnUse"><stop class="bmcblacal"/><stop offset="1" class="d0kv1cyul"/></linearGradient><linearGradient id="icz1zvE" x1="14.967" x2="15.08" y1="7.583" y2="7.599" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="iNhEkpd" x1="12.781" x2="12.967" y1="7.34" y2="7.401" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iQXkWfo" x1="16.114" x2="16.021" y1="15.498" y2="14.248" gradientUnits="userSpaceOnUse"><stop class="ky5pzdbbm"/><stop offset="1" class="giu-ixb2s"/></linearGradient><linearGradient id="i3Ic41b" x1="13.755" x2="14.607" y1="15.209" y2="15.209" gradientUnits="userSpaceOnUse"><stop class="uk2nrwb0k"/><stop offset="1" class="uy34yibrn"/></linearGradient><linearGradient id="i9YQGId" x1="10.306" x2="16.786" y1="24.826" y2="18.889" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="ihomYBd" x1="16.782" x2="16.274" y1="6.996" y2="4.107" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><filter id="iZfKKYb" width="7.28" height="8.609" x="14.724" y="19.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_243" result="effect2_innerShadow_4002_243"/></filter><filter id="i6eLO5d" width="5.734" height="7.279" x="15.195" y="20.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_243" stdDeviation=".25"/></filter><filter id="i38ZE0b" width="11.64" height="10.135" x="7.83" y="17.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="iDGM5Rd" width="4.352" height="2.364" x="7.83" y="25.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="iNsutqZ" width="3.579" height="3.542" x="20.591" y="24.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="i4BqQsb" width="4.443" height="5.249" x="11.944" y="5.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.172549 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="iR4nwce" width="5.586" height="5.499" x="12.123" y="3.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="iQzsDBb" width="1.013" height=".568" x="12.705" y="6.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="iE6vAEe" width="6.876" height="3.179" x="9.905" y="14.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="iDgPRwd" width="1.071" height="1.439" x="9.571" y="17.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="igaStTd" width="1.196" height="1.065" x="9.926" y="17.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_243"/></filter><filter id="iglaexC" width="8.168" height="8.42" x="9.556" y="18.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_243" stdDeviation=".375"/></filter><filter id="i3fDUlb" width="2.31" height="3.475" x="15.33" y="4.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_243" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-kneeling-dark" /></template>
<style>
.al52zb3wa {
  stop-color: var(--svg-color--5d4b4a, #5D4B4A);
}

.ao1jy03ok {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M14.73 25.616c-.05-1.838.196-4.493.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.265c1.062-.265 2.578-.171 3.765-.117l.39 1.516c-1.233.125-3.339.522-3.843.648c-.562.141-2.371.086-2.43-2.046");
}

.b1kejtblj {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M11.77 26.517a6.3 6.3 0 0 0-1.413-.642l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bm70d-gaq {
  stop-color: var(--svg-color--574241, #574241);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.cic7ureox {
  stop-color: var(--svg-color--e54d24, #E54D24);
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.d0kv1cyul {
  stop-color: var(--svg-color--5b4542, #5B4542);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dnobedcnj {
  d: path("M13.677 13.127c-.162 1.15-.094 2.637.016 3.528v1.289h5.031c-.055-2.063-.578-4.729-1.367-6.047c-.664-1.11-1.422-1.176-2.055-.957c-.605.183-1.422.75-1.625 2.187");
}

.dxj6ueb5g {
  d: path("M14.73 25.616c-.05-1.838.196-4.493.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.265c1.062-.265 2.578-.171 3.765-.117l.39 1.516c-1.233.125-3.339.522-3.843.648c-.562.141-2.371.086-2.43-2.046");
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

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
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

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
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

.l40jxvb0l {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M13.19 6.697a.8.8 0 0 0-.216-.016a.15.15 0 0 1-.037-.298c.07-.008.187-.006.313.02c.127.025.277.076.408.173a.15.15 0 0 1-.178.24a.7.7 0 0 0-.29-.12");
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.mmevalcjp {
  d: path("m21.476 24.764l-.885.75l.406 1.5c.39.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.179 0-.257l-2.285-2.769a.25.25 0 0 0-.355-.031");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.naoj9jbij {
  stop-color: var(--svg-color--544340, #544340);
  stop-opacity: 0;
}

.ndh-ggbqf {
  stop-color: var(--svg-color--544340, #544340);
}

.nhpz1ukdc {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.208 20.592c-.138.941-.573 3.263-1.239 5.338a.5.5 0 0 0 .152.535a.55.55 0 0 0 .538.085c.689-.243 2.053-.526 3.737-.302");
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

.numeh5b7w {
  stop-color: var(--svg-color--443534, #443534);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.om366ybrp {
  stop-color: var(--svg-color--3d292a, #3D292A);
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

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
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

.s75d29q8s {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("m10.599 17.147l.043.633a4.3 4.3 0 0 0-.603.608a.27.27 0 0 1-.346.058a.243.243 0 0 1-.085-.338c.312-.472.795-.844.99-.961");
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
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

.tp6928c8i {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("M10.552 17.744c.325-.003.516.179.57.27a2.2 2.2 0 0 0-.65.567c-.1.124-.278.169-.413.086a.266.266 0 0 1-.079-.39c.257-.329.48-.49.572-.533");
}

.ty__8ybpi {
  d: path("M11.77 26.517a6.3 6.3 0 0 0-1.413-.642l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.tzj-vacfb {
  d: path("m14.85 8.39l.2-1.44a.727.727 0 0 1-.2 1.44");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uk2nrwb0k {
  stop-color: var(--svg-color--d36030, #D36030);
}

.um92ahxqy {
  d: path("M16.033 6.032c.351.552.633 1.1.75 1.352a2.9 2.9 0 0 0 .28-2.07c-.113-.49-.788-.534-1.104-.145c-.229.28-.12.557.074.863");
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

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
}

.v3e60lbxs {
  d: path("M9.236 21.108c.137.575.807 3.427 1.125 4.78c-.573.233-1.39.67-2.067 1.009c-.324.162-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.17c1.787.443 3.937.81 5.747.262c1.2-.362 1.266-1.816 1.266-2.875l-7.61.079a2.726 2.726 0 0 0-1.874 3.125");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.wk6z7-t0m {
  fill: var(--svg-color--493033, #493033);
  d: path("m14.685 16.076l-.04-.78l1.891-.126c.047.664.118 1.594-.148 1.984c-.266.391-.765.859-2.2.946a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.039-.192.39-.568.79-.711c1.254-.45 2.96-.82 3.988-.95");
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

.xky7n8z-u {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M13.424 8.843a.125.125 0 0 1-.002.177c-.238.234-.583.293-.692.305a.125.125 0 1 1-.026-.25c.094-.009.367-.061.543-.234a.125.125 0 0 1 .177.002");
}

.xojzxxboq {
  stop-color: var(--svg-color--574241, #574241);
  stop-opacity: 0;
}

.xu4oisaxz {
  stop-color: var(--svg-color--cd5a3b, #CD5A3B);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.yqah6ebzx {
  stop-color: var(--svg-color--443534, #443534);
  stop-opacity: 0;
}

.zgjycebbf {
  stop-color: var(--svg-color--ff6e34, #FF6E34);
}

</style>
