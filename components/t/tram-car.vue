<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#izWmuuM)"><path fill="url(#ioZsiRb)" class="i6z8ygsko"/><path fill="url(#iafDfje)" class="i6z8ygsko"/><path fill="url(#igwIY5c)" class="i6z8ygsko"/><path fill="url(#iVzn2Mb)" class="i6z8ygsko"/><path fill="url(#ik0GUNZ)" class="i6z8ygsko"/></g><g filter="url(#iDnRmJb)"><path fill="url(#ixYsODe)" class="i4ycqhbqo"/><path fill="url(#iVE7Htc)" class="i4ycqhbqo"/></g><g filter="url(#i3fPmQb)"><path fill="url(#i8DuCIe)" class="vdk0-lbfn"/><path fill="url(#i8uKwia)" class="vdk0-lbfn"/></g><g filter="url(#i1X6a4b)"><mask id="itcuSbg" class="n1mjunbsu"><path class="dp6o1aczi"/></mask><path class="sin6j9bhx"/><path mask="url(#itcuSbg)" class="jfe59ab0l"/></g><g filter="url(#iJhE04c)"><mask id="iYKuhud" class="n1mjunbsu"><path class="r_vazp0-c"/></mask><path class="ljmwurbdw"/><path mask="url(#iYKuhud)" class="rnc46sxjk"/></g><g filter="url(#ihkDTHc)"><path fill="url(#ibpguVB)" class="uf25fgbym"/><path fill="url(#il0v58b)" class="uf25fgbym"/></g><g filter="url(#ivzmHHc)"><path fill="url(#iQb0yle)" class="e_-lnpbap"/><path fill="url(#ikOJ2FZ)" class="e_-lnpbap"/></g><g filter="url(#iPa7ZHe)"><path fill="url(#iZHfefr)" class="wcar8vbai"/><path fill="url(#i7pCG2d)" class="wcar8vbai"/></g><g filter="url(#iytYRqd)"><mask id="iqvfk0d" class="n1mjunbsu"><path class="xjnoeablo"/></mask><path class="i8bs7ccgh"/><path mask="url(#iqvfk0d)" class="m2hauxb1x"/></g><g filter="url(#i4caxie)"><mask id="iNmbJse" class="n1mjunbsu"><path class="hs94i6ixw"/></mask><path class="tq-6qzbpv"/><path mask="url(#iNmbJse)" class="wmtno_b2b"/></g><g filter="url(#iddouBb)"><path fill="url(#iBSvzne)" class="cfy3f8t4h"/><path fill="url(#isp6tXd)" class="cfy3f8t4h"/></g><g clip-rule="evenodd" filter="url(#iv6bZZh)" class="d2kvgvbvc"><path fill="url(#iHHrvuc)" class="qmtt-ebne"/><path fill="url(#iylZzke)" class="qmtt-ebne"/></g><g filter="url(#i1rBV9c)"><path fill="url(#ihMrfde)" class="hgt1bnxmm"/><path fill="url(#ieSOepb)" class="hgt1bnxmm"/></g><path fill="url(#iOnuBPI)" class="hgt1bnxmm"/><g filter="url(#i4RV9jb)"><path fill="url(#iAUMvpb)" class="qslb4eb4s"/></g><g filter="url(#ivGLx3b)"><path fill="url(#iKcd7Ku)" class="t3eacf5ol"/></g><path fill="url(#iAemYqu)" class="t3eacf5ol"/><g filter="url(#iPyBKtc)"><path fill="url(#ik5Micb)" class="e1w60ybtf"/></g><g filter="url(#iF6OE7d)"><path fill="url(#i4y6Cie)" class="jfsq6rb0d"/><path fill="url(#ioU9vgb)" class="jfsq6rb0d"/></g><g filter="url(#iEVi4IK)"><path fill="url(#i4u4TpN)" class="xb6l8lb1i"/><path fill="url(#iCCLvoG)" class="xb6l8lb1i"/></g><path fill="url(#iOElT2d)" class="tjkgaelnd"/><path fill="url(#iEmYRmb)" class="tjkgaelnd"/><path fill="url(#izKl11b)" class="ue94w6bcu"/><path fill="url(#i2IBEmG)" class="mlkma0_hb"/><g filter="url(#iDWNzWE)"><path fill="url(#iYEJIlc)" class="im4tp6bji"/></g><g filter="url(#iaWgvxd)"><path class="j8c6o_b8d"/></g><g filter="url(#iAv9jze)"><path stroke="url(#ifJQyxc)" class="ln3mlac-v"/></g><defs><linearGradient id="iafDfje" x1="29.99" x2="20.26" y1="4.934" y2="4.934" gradientUnits="userSpaceOnUse"><stop class="zccr59p_u"/><stop offset="1" class="q0eejondz"/></linearGradient><linearGradient id="igwIY5c" x1="30.275" x2="28.902" y1="4.235" y2="4.235" gradientUnits="userSpaceOnUse"><stop class="tccptpvfu"/><stop offset="1" class="a_av56b4u"/></linearGradient><linearGradient id="ixYsODe" x1="5.534" x2="5.534" y1="27.882" y2="25.668" gradientUnits="userSpaceOnUse"><stop class="gsgih1bnv"/><stop offset="1" class="v3huojbul"/><stop offset="1" class="v3huojbul"/></linearGradient><linearGradient id="iVE7Htc" x1="4.98" x2="4.98" y1="25.615" y2="26.178" gradientUnits="userSpaceOnUse"><stop class="aud6vekau"/><stop offset="1" class="k2o8gbbzl"/></linearGradient><linearGradient id="i8DuCIe" x1="11.044" x2="11.044" y1="27.882" y2="25.668" gradientUnits="userSpaceOnUse"><stop class="gsgih1bnv"/><stop offset="1" class="v3huojbul"/><stop offset="1" class="v3huojbul"/></linearGradient><linearGradient id="i8uKwia" x1="10.49" x2="10.49" y1="25.615" y2="26.178" gradientUnits="userSpaceOnUse"><stop class="aud6vekau"/><stop offset="1" class="k2o8gbbzl"/></linearGradient><linearGradient id="il0v58b" x1="5.49" x2="9.393" y1="26.382" y2="26.382" gradientUnits="userSpaceOnUse"><stop class="z8ke9ww_y"/><stop offset="1" class="pxdi5ttoe"/></linearGradient><linearGradient id="iQb0yle" x1="20.024" x2="20.024" y1="27.882" y2="25.668" gradientUnits="userSpaceOnUse"><stop class="gsgih1bnv"/><stop offset="1" class="v3huojbul"/><stop offset="1" class="v3huojbul"/></linearGradient><linearGradient id="ikOJ2FZ" x1="19.47" x2="19.47" y1="25.615" y2="26.178" gradientUnits="userSpaceOnUse"><stop class="aud6vekau"/><stop offset="1" class="k2o8gbbzl"/></linearGradient><linearGradient id="iZHfefr" x1="25.534" x2="25.534" y1="27.882" y2="25.668" gradientUnits="userSpaceOnUse"><stop class="gsgih1bnv"/><stop offset="1" class="v3huojbul"/><stop offset="1" class="v3huojbul"/></linearGradient><linearGradient id="i7pCG2d" x1="24.98" x2="24.98" y1="25.615" y2="26.178" gradientUnits="userSpaceOnUse"><stop class="aud6vekau"/><stop offset="1" class="k2o8gbbzl"/></linearGradient><linearGradient id="isp6tXd" x1="19.98" x2="23.883" y1="26.382" y2="26.382" gradientUnits="userSpaceOnUse"><stop class="z8ke9ww_y"/><stop offset="1" class="pxdi5ttoe"/></linearGradient><linearGradient id="iHHrvuc" x1="14.824" x2="17.154" y1="5.782" y2="5.782" gradientUnits="userSpaceOnUse"><stop class="zzfe845-e"/><stop offset="1" class="z16-b1bjm"/></linearGradient><linearGradient id="iylZzke" x1="17.362" x2="16.936" y1="4.918" y2="5.346" gradientUnits="userSpaceOnUse"><stop class="bfq-7hb2l"/><stop offset="1" class="qj-nntbbe"/></linearGradient><linearGradient id="ihMrfde" x1="5.976" x2="25.977" y1="7.885" y2="7.885" gradientUnits="userSpaceOnUse"><stop class="s6rfbdbpk"/><stop offset="1" class="hw8zt9beq"/></linearGradient><linearGradient id="ieSOepb" x1="5.98" x2="7.345" y1="8.882" y2="8.882" gradientUnits="userSpaceOnUse"><stop class="n3yz20bei"/><stop offset="1" class="huzgt9bpc"/></linearGradient><linearGradient id="iAUMvpb" x1="1.976" x2="29.98" y1="14.385" y2="14.385" gradientUnits="userSpaceOnUse"><stop class="jljj9x1nl"/><stop offset="1" class="rr16fpbgs"/></linearGradient><linearGradient id="iKcd7Ku" x1="29.966" x2="1.976" y1="22.885" y2="22.885" gradientUnits="userSpaceOnUse"><stop class="x4dmv3bct"/><stop offset="1" class="ql42zk0jd"/></linearGradient><linearGradient id="iAemYqu" x1="29.97" x2="28.825" y1="22.882" y2="22.882" gradientUnits="userSpaceOnUse"><stop class="qyt4ftfvj"/><stop offset="1" class="laqc_gbkw"/></linearGradient><linearGradient id="ik5Micb" x1="2.449" x2="6.783" y1="18.36" y2="15.703" gradientUnits="userSpaceOnUse"><stop class="b2vf64baw"/><stop offset="1" class="z716gpu2s"/></linearGradient><linearGradient id="i4y6Cie" x1="9.55" x2="13.695" y1="17.481" y2="13.972" gradientUnits="userSpaceOnUse"><stop class="ms17afuvh"/><stop offset="1" class="ki2kxsb7t"/></linearGradient><linearGradient id="ioU9vgb" x1="8.706" x2="10.237" y1="14.907" y2="14.907" gradientUnits="userSpaceOnUse"><stop class="wcqynik-m"/><stop offset="1" class="qvwsy-b-u"/></linearGradient><linearGradient id="i4u4TpN" x1="17.55" x2="21.695" y1="17.481" y2="13.972" gradientUnits="userSpaceOnUse"><stop class="ms17afuvh"/><stop offset="1" class="ki2kxsb7t"/></linearGradient><linearGradient id="iCCLvoG" x1="16.706" x2="18.237" y1="14.907" y2="14.907" gradientUnits="userSpaceOnUse"><stop class="wcqynik-m"/><stop offset="1" class="qvwsy-b-u"/></linearGradient><linearGradient id="iOElT2d" x1="24.974" x2="29.968" y1="15.385" y2="15.385" gradientUnits="userSpaceOnUse"><stop class="eevydib3x"/><stop offset="1" class="xlultxbwl"/></linearGradient><linearGradient id="izKl11b" x1="5.612" x2="29.98" y1="29.872" y2="29.872" gradientUnits="userSpaceOnUse"><stop class="lyg3dpbep"/><stop offset="1" class="vqnuiabrd"/></linearGradient><linearGradient id="i2IBEmG" x1="1.976" x2="3.397" y1="21.885" y2="21.885" gradientUnits="userSpaceOnUse"><stop class="vntyuib5k"/><stop offset="1" class="bvs2scbrk"/></linearGradient><linearGradient id="iYEJIlc" x1="2.695" x2="29.265" y1="28.872" y2="28.872" gradientUnits="userSpaceOnUse"><stop class="mums5cbhz"/><stop offset="1" class="xno1hrb_w"/></linearGradient><linearGradient id="ifJQyxc" x1="25.815" x2="25.815" y1="18.135" y2="14.015" gradientUnits="userSpaceOnUse"><stop class="bi3dm3lvv"/><stop offset="1" class="e6y49peht"/></linearGradient><filter id="izWmuuM" width="28.61" height="2.17" x="1.98" y="2.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.356863 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="iDnRmJb" width="4.2" height="4.15" x="3.88" y="23.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0470588 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0470588 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9715" result="effect2_innerShadow_18_9715"/></filter><filter id="i3fPmQb" width="4.2" height="4.15" x="9.39" y="23.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0470588 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0470588 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9715" result="effect2_innerShadow_18_9715"/></filter><filter id="i1X6a4b" width="2.328" height="1.5" x="9.361" y="25.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9715" stdDeviation=".125"/></filter><filter id="iJhE04c" width="2.99" height="1.5" x="5.201" y="25.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9715" stdDeviation=".125"/></filter><filter id="ihkDTHc" width="6" height="1" x="5.49" y="25.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.341176 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="ivzmHHc" width="4.2" height="4.15" x="18.37" y="23.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0470588 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0470588 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9715" result="effect2_innerShadow_18_9715"/></filter><filter id="iPa7ZHe" width="4.2" height="4.15" x="23.88" y="23.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0470588 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0470588 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9715" result="effect2_innerShadow_18_9715"/></filter><filter id="iytYRqd" width="2.99" height="1.5" x="19.662" y="25.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9715" stdDeviation=".125"/></filter><filter id="i4caxie" width="2.328" height="1.5" x="23.796" y="25.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9715" stdDeviation=".125"/></filter><filter id="iddouBb" width="6" height="1" x="19.98" y="25.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.341176 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="iv6bZZh" width="3.873" height="3.67" x="14.098" y="3.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="i1rBV9c" width="20.25" height="3.198" x="5.98" y="6.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.411765 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="i4RV9jb" width="29.2" height="12.637" x="1.38" y="8.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.964706 0 0 0 0 0.988235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.576471 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9715" result="effect2_innerShadow_18_9715"/></filter><filter id="ivGLx3b" width="27.99" height="6.5" x="1.98" y="19.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.027451 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="iPyBKtc" width="6.27" height="8" x=".73" y="11.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25" dy="1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.6 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="iF6OE7d" width="6.74" height="6.55" x="8.24" y="11.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.6 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="iEVi4IK" width="6.74" height="6.55" x="16.24" y="11.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.6 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9715"/></filter><filter id="iDWNzWE" width="27.77" height="1.716" x="2.095" y="27.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9715" stdDeviation=".3"/></filter><filter id="iaWgvxd" width="1.075" height="1.068" x="14.915" y="5.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9715" stdDeviation=".05"/></filter><filter id="iAv9jze" width="1.5" height="5.428" x="24.979" y="13.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9715" stdDeviation=".25"/></filter><radialGradient id="ioZsiRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1221 -42.3018 0 23.06 3.307)" gradientUnits="userSpaceOnUse"><stop class="p3en57bzh"/><stop offset="1" class="tbjop9b-y"/></radialGradient><radialGradient id="iVzn2Mb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8894 1.01 -.9057 -.79756 30.213 2.914)" gradientUnits="userSpaceOnUse"><stop class="tccptpvfu"/><stop offset="1" class="a_av56b4u"/></radialGradient><radialGradient id="ik0GUNZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55838 .74715 -.3997 -.83367 14.928 5.087)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="ysex4gb5g"/><stop offset="1" class="ufbnu2bmf"/></radialGradient><radialGradient id="ibpguVB" cx="0" cy="0" r="1" gradientTransform="matrix(5.18722 0 0 .60043 6.298 25.88)" gradientUnits="userSpaceOnUse"><stop class="azaxdfjjn"/><stop offset="1" class="tnz914bvq"/></radialGradient><radialGradient id="iBSvzne" cx="0" cy="0" r="1" gradientTransform="matrix(5.18722 0 0 .60043 20.788 25.88)" gradientUnits="userSpaceOnUse"><stop class="azaxdfjjn"/><stop offset="1" class="tnz914bvq"/></radialGradient><radialGradient id="iOnuBPI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29667 0 0 -8.10796 25.98 10.08)" gradientUnits="userSpaceOnUse"><stop class="vj-z_y6he"/><stop offset="1" class="a7fb3xngl"/></radialGradient><radialGradient id="iEmYRmb" cx="0" cy="0" r="1" gradientTransform="matrix(5.55258 -.8966 .3502 2.16879 24.98 12.265)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="ly6oa1bpd"/><stop offset="1" class="eb74mybmd"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tram-car" /></template>
<style>
.a_av56b4u {
  stop-color: var(--svg-color--e6e5e8, #E6E5E8);
  stop-opacity: 0;
}

.a7fb3xngl {
  stop-color: var(--svg-color--dedcdf, #DEDCDF);
  stop-opacity: 0;
}

.aud6vekau {
  stop-color: var(--svg-color--382340, #382340);
}

.azaxdfjjn {
  stop-color: var(--svg-color--cfb6d9, #CFB6D9);
}

.b2vf64baw {
  stop-color: var(--svg-color--45d4ff, #45D4FF);
}

.bfq-7hb2l {
  stop-color: var(--svg-color--8f79a0, #8F79A0);
}

.bi3dm3lvv {
  stop-color: var(--svg-color--4de3ff, #4DE3FF);
}

.bvs2scbrk {
  stop-color: var(--svg-color--eb552a, #EB552A);
}

.cfy3f8t4h {
  d: path("M25.48 26.382h-5c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h5c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dp6o1aczi {
  d: path("M9.624 25.335h1.448c.206 0 .367.22.367.5s-.161.5-.367.5H9.713a2.6 2.6 0 0 1-.09-1");
}

.e_-lnpbap {
  d: path("M20.47 27.882a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.e1w60ybtf {
  d: path("M5.9 11.882H1.98v7H5.9c.61 0 1.1-.49 1.1-1.1v-4.8c-.01-.6-.5-1.1-1.1-1.1");
}

.e6y49peht {
  stop-color: var(--svg-color--4de3ff, #4DE3FF);
  stop-opacity: 0;
}

.eb74mybmd {
  stop-color: var(--svg-color--269af3, #269AF3);
  stop-opacity: 0;
}

.eevydib3x {
  stop-color: var(--svg-color--3fcdff, #3FCDFF);
}

.ft5dv1b6b {
  fill: none;
}

.gsgih1bnv {
  stop-color: var(--svg-color--483e4e, #483E4E);
}

.hgt1bnxmm {
  d: path("M24.79 6.882H7.16c-.65 0-1.18.53-1.18 1.18v2.019h20V8.062c0-.65-.53-1.18-1.19-1.18");
}

.hs94i6ixw {
  d: path("M24.059 25.335h1.448c.205 0 .367.22.367.5s-.162.5-.367.5h-1.36a2.6 2.6 0 0 1-.088-1");
}

.huzgt9bpc {
  stop-color: var(--svg-color--69696a, #69696A);
  stop-opacity: 0;
}

.hw8zt9beq {
  stop-color: var(--svg-color--c1bcc4, #C1BCC4);
}

.i4ycqhbqo {
  d: path("M5.98 27.882a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.i6z8ygsko {
  d: path("M28.98 4.934H2.99c-.56 0-1.01-.45-1.01-1.01s.45-1.01 1.01-1.01h25.99c.56 0 1.01.45 1.01 1.01a1.02 1.02 0 0 1-1.01 1.01");
}

.i8bs7ccgh {
  fill: var(--svg-color--34253e, #34253E);
  d: path("M22.384 25.406h-1.972c-.28 0-.5.22-.5.5s.22.5.5.5h1.85a2 2 0 0 0 .122-1");
}

.im4tp6bji {
  d: path("M2.695 28.356h26.57v.516H2.695z");
}

.j8c6o_b8d {
  stroke: var(--svg-color--685e71, #685E71);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m15.05 5.934l.804.797");
}

.jfe59ab0l {
  fill: var(--svg-color--000, #000);
  d: path("m9.624 25.335l-.995-.097l.088-.903h.907zm.09 1v1h-.752l-.21-.721zm1.358 0H9.624v-2h1.448zm-.633-.5c0 .044.012.134.088.237a.68.68 0 0 0 .545.263v-2c.489 0 .856.267 1.067.553c.208.284.3.623.3.947zm.633-.5a.68.68 0 0 0-.545.263a.4.4 0 0 0-.088.237h2a1.6 1.6 0 0 1-.3.947c-.21.287-.578.553-1.067.553zm-1.359 0h1.36v2h-1.36zm-.96 1.279A3.6 3.6 0 0 1 8.61 25.6h2q.002.25.063.456zM8.61 25.6q0-.184.018-.363l1.99.194q-.008.082-.008.169z");
}

.jfsq6rb0d {
  d: path("M13.88 11.882h-3.79c-.61 0-1.1.49-1.1 1.1v3.85c0 .61.49 1.1 1.1 1.1h3.79c.61 0 1.1-.49 1.1-1.1v-3.85c0-.6-.49-1.1-1.1-1.1");
}

.jljj9x1nl {
  stop-color: var(--svg-color--c3bbc8, #C3BBC8);
}

.k2o8gbbzl {
  stop-color: var(--svg-color--382340, #382340);
  stop-opacity: 0;
}

.ki2kxsb7t {
  stop-color: var(--svg-color--3fbeff, #3FBEFF);
}

.laqc_gbkw {
  stop-color: var(--svg-color--f24993, #F24993);
  stop-opacity: 0;
}

.ljmwurbdw {
  fill: var(--svg-color--34253e, #34253E);
  d: path("M7.923 25.406H5.951c-.28 0-.5.22-.5.5s.22.5.5.5H7.8a2 2 0 0 0 .122-1");
}

.ln3mlac-v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M25.73 18.135v-3.928");
}

.ly6oa1bpd {
  stop-color: var(--svg-color--269af3, #269AF3);
}

.lyg3dpbep {
  stop-color: var(--svg-color--2b1842, #2B1842);
}

.m2hauxb1x {
  fill: var(--svg-color--000, #000);
  d: path("m22.384 25.406l.992-.132l-.116-.869h-.876zm-.121 1v1h.68l.25-.633zm-1.851 0h1.972v-2h-1.972zm.5-.5c0 .272-.228.5-.5.5v-2c-.832 0-1.5.667-1.5 1.5zm-.5-.5c.272 0 .5.227.5.5h-2c0 .832.668 1.5 1.5 1.5zm1.85 0h-1.85v2h1.85zm.93 1.367c.136-.343.21-.715.21-1.102h-2a1 1 0 0 1-.07.367zm.21-1.102q0-.201-.026-.397l-1.983.263q.009.066.009.134z");
}

.mlkma0_hb {
  d: path("M2.98 22.882h-1v-2h1c.55 0 1 .45 1 1c0 .56-.45 1-1 1");
}

.ms17afuvh {
  stop-color: var(--svg-color--44d8ff, #44D8FF);
}

.mums5cbhz {
  stop-color: var(--svg-color--423458, #423458);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n3yz20bei {
  stop-color: var(--svg-color--69696a, #69696A);
}

.p3en57bzh {
  stop-color: var(--svg-color--c4bec8, #C4BEC8);
}

.pxdi5ttoe {
  stop-color: var(--svg-color--817187, #817187);
  stop-opacity: 0;
}

.q0eejondz {
  stop-color: var(--svg-color--cac8cb, #CAC8CB);
  stop-opacity: 0;
}

.qj-nntbbe {
  stop-color: var(--svg-color--8f79a0, #8F79A0);
  stop-opacity: 0;
}

.ql42zk0jd {
  stop-color: var(--svg-color--ff3f62, #FF3F62);
}

.qmtt-ebne {
  d: path("m16.69 4.329l.782.782c.582.518.48.98 0 1.428l-.782.783a1.01 1.01 0 0 1-1.428 0l-.782-.783c-.543-.48-.473-.996 0-1.428l.782-.782c.527-.551 1.01-.465 1.428 0m-.707.707a.01.01 0 0 0-.014 0l-.782.782a.01.01 0 0 0 0 .014l.782.783a.01.01 0 0 0 .014 0l.782-.783a.01.01 0 0 0 0-.014z");
}

.qslb4eb4s {
  d: path("m29.98 10.882l-.01-.96c-.06-.59-.55-1.04-1.15-1.04H3.14c-.64 0-1.16.52-1.16 1.16V20.92h27.99z");
}

.qvwsy-b-u {
  stop-color: var(--svg-color--4ae1ff, #4AE1FF);
  stop-opacity: 0;
}

.qyt4ftfvj {
  stop-color: var(--svg-color--f24993, #F24993);
}

.r_vazp0-c {
  d: path("M7.923 25.406H5.951c-.28 0-.5.22-.5.5s.22.5.5.5H7.8a2 2 0 0 0 .122-1");
}

.rnc46sxjk {
  fill: var(--svg-color--000, #000);
  d: path("m7.923 25.406l.992-.132l-.116-.869h-.876zm-.121 1v1h.68l.25-.633zm-1.851 0h1.972v-2H5.951zm.5-.5c0 .272-.228.5-.5.5v-2c-.832 0-1.5.667-1.5 1.5zm-.5-.5c.272 0 .5.227.5.5h-2c0 .832.668 1.5 1.5 1.5zm1.85 0h-1.85v2H7.8zm.93 1.367c.136-.343.21-.715.21-1.102h-2a1 1 0 0 1-.07.367zm.21-1.102a3 3 0 0 0-.026-.397l-1.983.263q.009.066.009.134z");
}

.rr16fpbgs {
  stop-color: var(--svg-color--ddd3e4, #DDD3E4);
}

.s6rfbdbpk {
  stop-color: var(--svg-color--99969b, #99969B);
}

.sin6j9bhx {
  fill: var(--svg-color--34253e, #34253E);
  d: path("M9.624 25.335h1.448c.206 0 .367.22.367.5s-.161.5-.367.5H9.713a2.6 2.6 0 0 1-.09-1");
}

.t3eacf5ol {
  d: path("M1.98 19.882v4.96c.06.59.55 1.04 1.15 1.04h25.68c.64 0 1.16-.52 1.16-1.16v-4.84z");
}

.tbjop9b-y {
  stop-color: var(--svg-color--8f8c92, #8F8C92);
}

.tccptpvfu {
  stop-color: var(--svg-color--e6e5e8, #E6E5E8);
}

.tjkgaelnd {
  d: path("M29.97 11.882h-3.89c-.61 0-1.1.49-1.1 1.1v4.8c0 .61.49 1.1 1.1 1.1h3.89z");
}

.tnz914bvq {
  stop-color: var(--svg-color--a28dad, #A28DAD);
}

.tq-6qzbpv {
  fill: var(--svg-color--34253e, #34253E);
  d: path("M24.059 25.335h1.448c.205 0 .367.22.367.5s-.162.5-.367.5h-1.36a2.6 2.6 0 0 1-.088-1");
}

.ue94w6bcu {
  d: path("M29.98 27.872h-28v2h28z");
}

.uf25fgbym {
  d: path("M10.99 26.382h-5c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h5c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.ufbnu2bmf {
  stop-color: var(--svg-color--58565a, #58565A);
  stop-opacity: 0;
}

.v3huojbul {
  stop-color: var(--svg-color--45344f, #45344F);
}

.vdk0-lbfn {
  d: path("M11.49 27.882a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.vj-z_y6he {
  stop-color: var(--svg-color--dedcdf, #DEDCDF);
}

.vntyuib5k {
  stop-color: var(--svg-color--ffaa17, #FFAA17);
}

.vqnuiabrd {
  stop-color: var(--svg-color--5e3783, #5E3783);
}

.wcar8vbai {
  d: path("M25.98 27.882a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.wcqynik-m {
  stop-color: var(--svg-color--4ae1ff, #4AE1FF);
}

.wmtno_b2b {
  fill: var(--svg-color--000, #000);
  d: path("m24.059 25.335l-.996-.097l.088-.903h.908zm.089 1v1h-.751l-.21-.721zm1.359 0h-1.448v-2h1.448zm-.633-.5a.4.4 0 0 0 .087.237a.68.68 0 0 0 .546.263v-2c.488 0 .856.267 1.066.553c.209.284.3.623.3.947zm.633-.5a.68.68 0 0 0-.546.263a.4.4 0 0 0-.087.237h2a1.6 1.6 0 0 1-.3.947a1.33 1.33 0 0 1-1.067.553zm-1.36 0h1.36v2h-1.36zm-.96 1.279a3.6 3.6 0 0 1-.141-1.013h2q.002.25.062.456zm-.141-1.013q0-.184.017-.363l1.99.194q-.006.082-.007.169z");
}

.x4dmv3bct {
  stop-color: var(--svg-color--e53b87, #E53B87);
}

.xb6l8lb1i {
  d: path("M21.88 11.882h-3.79c-.61 0-1.1.49-1.1 1.1v3.85c0 .61.49 1.1 1.1 1.1h3.79c.61 0 1.1-.49 1.1-1.1v-3.85c0-.6-.49-1.1-1.1-1.1");
}

.xjnoeablo {
  d: path("M22.384 25.406h-1.972c-.28 0-.5.22-.5.5s.22.5.5.5h1.85a2 2 0 0 0 .122-1");
}

.xlultxbwl {
  stop-color: var(--svg-color--40c3ff, #40C3FF);
}

.xno1hrb_w {
  stop-color: var(--svg-color--694596, #694596);
}

.ysex4gb5g {
  stop-color: var(--svg-color--58565a, #58565A);
}

.z16-b1bjm {
  stop-color: var(--svg-color--745f85, #745F85);
}

.z716gpu2s {
  stop-color: var(--svg-color--3bb4ff, #3BB4FF);
}

.z8ke9ww_y {
  stop-color: var(--svg-color--817187, #817187);
}

.zccr59p_u {
  stop-color: var(--svg-color--cac8cb, #CAC8CB);
}

.zzfe845-e {
  stop-color: var(--svg-color--504657, #504657);
}

</style>
