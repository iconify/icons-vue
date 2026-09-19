<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYT99Xc)"><path class="xtp18r_3e"/></g><g filter="url(#iWciXkx)"><path stroke="url(#iA2Bone)" class="f-t538xod"/></g><path fill="url(#iW6jIqc)" class="no3uypbod"/><g filter="url(#izDeZkd)"><path class="dgbnzbfzk"/></g><path fill="url(#igq7Qud)" class="m0qbo5zst"/><path fill="url(#i4Gyrqe)" class="m0qbo5zst"/><path fill="url(#ixxgrdb)" class="m26o0cchb"/><g filter="url(#iIa1uHB)"><path class="hhfjsojfs"/><path fill="url(#iFdtxUI)" class="jau71ebeh"/><path fill="url(#iapH3ib)" class="jau71ebeh"/></g><g filter="url(#iUEGVre)"><path class="j-ea5dyme"/><path fill="url(#iePJ2Nb)" class="fpd7yqbsk"/><path fill="url(#i0IsdHc)" class="fpd7yqbsk"/></g><path fill="url(#iSW4F7b)" transform="rotate(-14.867 13.886 9.386)" class="dzvqyybgq"/><path fill="url(#iaEkZWc)" transform="rotate(-14.867 13.886 9.386)" class="dzvqyybgq"/><path fill="url(#iRVKnnU)" transform="rotate(-14.867 13.886 9.386)" class="dzvqyybgq"/><path fill="url(#i82m2lb)" class="a3x9xrb8c"/><path fill="url(#iQVg4Nc)" class="a3x9xrb8c"/><path fill="url(#iqFGXAb)" class="a3x9xrb8c"/><g filter="url(#ifSjF2c)"><path class="usazw8ham"/><path fill="url(#io9eREr)" class="zaqgvq4le"/></g><g filter="url(#icA4kgd)"><path class="skjeal_ka"/></g><g filter="url(#igJMBPc)"><path class="l2ju9bcgt"/></g><path fill="url(#i1oai9d)" class="nve29hb1p"/><path fill="url(#iTDWode)" class="nve29hb1p"/><g filter="url(#ijJm22d)"><path fill="url(#iieX7Ob)" class="pnmvm92bz"/></g><path fill="url(#iDpU8fe)" class="rg5t0y_vv"/><g filter="url(#i1H9Q9J)"><path fill="url(#ilVJ7pd)" class="p26rrpb5e"/><path fill="url(#iXsbPgc)" class="p26rrpb5e"/><path fill="url(#iLkQsNc)" class="p26rrpb5e"/><path fill="url(#iCNJUab)" class="p26rrpb5e"/></g><g filter="url(#iuUQm5b)"><path fill="url(#iS3L5Pc)" class="fzmjltb3p"/><path fill="url(#iSiBOOd)" class="fzmjltb3p"/><path fill="url(#i6zQKOb)" class="fzmjltb3p"/></g><path fill="url(#i7n4wkg)" class="l9og9fbem"/><path fill="url(#inhMdFc)" class="l9og9fbem"/><path fill="url(#iIH7NPb)" class="l9og9fbem"/><path clip-rule="evenodd" class="a7ml1i1fx"/><path class="a0l2uyncb"/><path fill="url(#iLVtCSc)" class="rstbkwref"/><path fill="url(#iEpsGoA)" class="swge0f8mu"/><ellipse fill="url(#ia5mu0U)" transform="rotate(24.61 12.696 7.335)" class="qilpy_bau"/><g filter="url(#ibC2Erc)"><path clip-rule="evenodd" class="oy1ldyvxm"/></g><defs><radialGradient id="iA2Bone" cx="0" cy="0" r="1" gradientTransform="matrix(3.48437 -4.05522 3.01176 2.5878 16.13 26.541)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iW6jIqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 3.29646 -1.78135 -.28708 16.224 20.19)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="i4Gyrqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 12.849 17.861)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="ixxgrdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 3.14063 -8.2876 -.28863 14.443 17.97)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iSW4F7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80956 4.93988 13.977 10.969)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="z4m0hk31o"/><stop offset="1" class="pp9y_ov5j"/></radialGradient><radialGradient id="iaEkZWc" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 5.038 9.717)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="ra4kqjbah"/><stop offset="1" class="ng2vn7s5c"/></radialGradient><radialGradient id="i82m2lb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4531 4.00002 -4.9949 -4.31194 17.677 13.486)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="b2o3a7r9l"/><stop offset="1" class="g7ee89odc"/></radialGradient><radialGradient id="iQVg4Nc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03122 3.14064 -3.13218 -2.02576 17.24 11.611)" gradientUnits="userSpaceOnUse"><stop class="oo0a8g8xe"/><stop offset="1" class="hc1x_wbbe"/></radialGradient><radialGradient id="iqFGXAb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73437 .23436 -.4261 -6.78981 17.162 15.236)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="brpomvbii"/><stop offset="1" class="lmk5_gb2n"/></radialGradient><radialGradient id="io9eREr" cx="0" cy="0" r="1" gradientTransform="rotate(86.947 .142 16.237)scale(2.34708 .80604)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="a3cmd2asj"/><stop offset="1" class="y3ztz7b1k"/></radialGradient><radialGradient id="iTDWode" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 1.04686 -.99542 -1.2183 16.797 11.611)" gradientUnits="userSpaceOnUse"><stop class="n6csxrxuy"/><stop offset="1" class="obkbkpctx"/></radialGradient><radialGradient id="iDpU8fe" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 .25781 -.36391 .67269 11.501 8.293)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="n304-r4kd"/><stop offset=".684" class="uk3jx7nau"/></radialGradient><radialGradient id="iXsbPgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 15.163 7.59)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jijo4-b9s"/><stop offset="1" class="ni_rkbnps"/></radialGradient><radialGradient id="iLkQsNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 12.267 8.778)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="dd9hd6bwg"/><stop offset="1" class="aw2d6h33n"/></radialGradient><radialGradient id="iCNJUab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 13.095 7.637)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jynvl5b3k"/><stop offset="1" class="b-jom1b0d"/></radialGradient><radialGradient id="iS3L5Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43749 3.12502 -3.54357 -3.89789 17.038 4.928)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="lgum6kbvi"/><stop offset="1" class="ri9ygtemw"/></radialGradient><radialGradient id="iSiBOOd" cx="0" cy="0" r="1" gradientTransform="rotate(81.634 5.179 12.64)scale(2.71158 1.19788)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="x4tqf8rmd"/><stop offset="1" class="m5kggdiwk"/></radialGradient><radialGradient id="i6zQKOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -.09375 .18397 2.94358 11.741 5.543)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="bd_cirbzn"/><stop offset="1" class="u8iayhb4j"/></radialGradient><radialGradient id="i7n4wkg" cx="0" cy="0" r="1" gradientTransform="rotate(-16.188 33.74 -48.781)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="inhMdFc" cx="0" cy="0" r="1" gradientTransform="matrix(.22596 1.17975 -1.22934 .23546 14.97 7.172)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="iLVtCSc" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.8 7.665)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iEpsGoA" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.632 7.686)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="iYT99Xc" width="7.28" height="8.609" x="14.724" y="19.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_248" result="effect2_innerShadow_4002_248"/></filter><filter id="iWciXkx" width="5.734" height="7.279" x="15.195" y="20.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_248" stdDeviation=".25"/></filter><filter id="izDeZkd" width="11.64" height="10.135" x="7.83" y="17.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/></filter><filter id="iIa1uHB" width="4.352" height="2.364" x="7.83" y="25.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/></filter><filter id="iUEGVre" width="3.579" height="3.542" x="20.591" y="24.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/></filter><filter id="ifSjF2c" width="6.876" height="3.179" x="9.905" y="14.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.345098 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_248" result="effect2_innerShadow_4002_248"/></filter><filter id="icA4kgd" width="1.071" height="1.439" x="9.571" y="17.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.290196 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/></filter><filter id="igJMBPc" width="1.196" height="1.065" x="9.926" y="17.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.290196 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/></filter><filter id="ijJm22d" width="8.168" height="8.42" x="9.556" y="18.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_248" stdDeviation=".375"/></filter><filter id="i1H9Q9J" width="4.443" height="5.249" x="11.788" y="5.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/></filter><filter id="iuUQm5b" width="6.391" height="5.479" x="11.355" y="3.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0862745 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_248" result="effect2_innerShadow_4002_248"/></filter><filter id="ibC2Erc" width="1.117" height=".648" x="12.492" y="6.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_248"/></filter><linearGradient id="igq7Qud" x1="16.786" x2="16.786" y1="17.767" y2="18.299" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iFdtxUI" x1="11.911" x2="10.927" y1="27.033" y2="27.033" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="iapH3ib" x1="10.474" x2="10.474" y1="27.896" y2="27.525" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iePJ2Nb" x1="20.936" x2="21.622" y1="24.986" y2="25.65" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="i0IsdHc" x1="23.083" x2="22.868" y1="26.189" y2="26.361" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iRVKnnU" x1="13.883" x2="14.119" y1="11.261" y2="11.255" gradientUnits="userSpaceOnUse"><stop class="ptopy6fga"/><stop offset="1" class="n03q6iq6j"/></linearGradient><linearGradient id="i1oai9d" x1="16.765" x2="14.275" y1="14.236" y2="14.314" gradientUnits="userSpaceOnUse"><stop class="ofo46gsuq"/><stop offset="1" class="lq0qk0brb"/></linearGradient><linearGradient id="iieX7Ob" x1="10.306" x2="16.787" y1="24.783" y2="18.846" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="ilVJ7pd" x1="14.851" x2="11.988" y1="8.332" y2="8.504" gradientUnits="userSpaceOnUse"><stop class="co18c5bwy"/><stop offset="1" class="kj_uw-bok"/></linearGradient><linearGradient id="iIH7NPb" x1="14.837" x2="15.118" y1="7.508" y2="7.586" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="ia5mu0U" x1="12.625" x2="12.811" y1="7.296" y2="7.357" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-kneeling-medium-dark" /></template>
<style>
.a0l2uyncb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.523 7.686h.988c0-.392-.221-.709-.494-.709s-.494.317-.494.709");
}

.a3cmd2asj {
  stop-color: var(--svg-color--906964, #906964);
}

.a3x9xrb8c {
  d: path("M13.677 13.084c-.162 1.15-.094 2.636.016 3.527v1.29h5.031c-.055-2.063-.578-4.73-1.367-6.048c-.664-1.11-1.422-1.176-2.055-.957c-.605.184-1.422.75-1.625 2.188");
}

.a7ml1i1fx {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.268 8.8a.125.125 0 0 1-.002.176c-.238.234-.582.294-.692.305a.125.125 0 1 1-.025-.249c.093-.01.366-.061.542-.234a.125.125 0 0 1 .177.002");
}

.aw2d6h33n {
  stop-color: var(--svg-color--9a7468, #9A7468);
  stop-opacity: 0;
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-jom1b0d {
  stop-color: var(--svg-color--845a4e, #845A4E);
  stop-opacity: 0;
}

.b2o3a7r9l {
  stop-color: var(--svg-color--45a7f8, #45A7F8);
}

.bd_cirbzn {
  stop-color: var(--svg-color--514342, #514342);
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.brpomvbii {
  stop-color: var(--svg-color--4b77af, #4B77AF);
  stop-opacity: 0;
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.co18c5bwy {
  stop-color: var(--svg-color--825756, #825756);
}

.dd9hd6bwg {
  stop-color: var(--svg-color--9d726c, #9D726C);
}

.dgbnzbfzk {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M9.236 21.064c.137.575.807 3.427 1.125 4.782c-.573.231-1.39.668-2.067 1.007c-.324.163-.533.496-.443.848a.26.26 0 0 0 .252.195h3.43a.25.25 0 0 0 .25-.252l-.076-7.17c1.787.443 3.937.809 5.747.262c1.2-.362 1.266-1.816 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.dzvqyybgq {
  d: path("M13.886 9.386h1.976v2.198h-1.976z");
}

.f-t538xod {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.208 20.549c-.138.94-.573 3.263-1.239 5.337a.5.5 0 0 0 .152.535a.55.55 0 0 0 .538.086c.689-.243 2.053-.526 3.737-.302");
}

.fpd7yqbsk {
  d: path("m21.476 24.72l-.885.75l.406 1.5c.39.198 1.35.654 2.063.891c.547.183.887.06 1.056-.083c.078-.066.066-.18 0-.258l-2.285-2.768a.25.25 0 0 0-.355-.032");
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

.fzmjltb3p {
  d: path("M12.655 6.14c-.656 0-.969-.372-1-.837c0-.656.501-.795.695-.816c.22-.024.305-.047.61-.262a.9.9 0 0 1 .91-.098c.148.07.476.106.71.035c.391-.117.696-.113.997.118c.209.16.363.16.613.16c.344 0 .636.154.856.32c.657.498.582 2.207.258 3.168c-.31.92-.778 1.027-1.168.992c-.47-.042-.59-.398-.66-.695c-.057-.238-.201-.99-.266-1.238c-.136-.062-.432-.085-.532-.473s-.492-.432-.757-.406c-.162.015-.61.031-1.266.031");
}

.g7ee89odc {
  stop-color: var(--svg-color--3370b9, #3370B9);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.hc1x_wbbe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
  stop-opacity: 0;
}

.hhfjsojfs {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M11.77 26.474a6.3 6.3 0 0 0-1.413-.642l.004.014c-.433.175-1.005.466-1.55.745q-.267.137-.517.262c-.324.163-.533.496-.443.848a.26.26 0 0 0 .252.195h3.43a.25.25 0 0 0 .25-.252z");
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.j-ea5dyme {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m21.476 24.72l-.885.75l.406 1.5c.39.198 1.35.654 2.063.891c.547.183.887.06 1.056-.083c.078-.066.066-.18 0-.258l-2.285-2.768a.25.25 0 0 0-.355-.032");
}

.jau71ebeh {
  d: path("M11.77 26.474a6.3 6.3 0 0 0-1.413-.642l.004.014c-.433.175-1.005.466-1.55.745q-.267.137-.517.262c-.324.163-.533.496-.443.848a.26.26 0 0 0 .252.195h3.43a.25.25 0 0 0 .25-.252z");
}

.jijo4-b9s {
  stop-color: var(--svg-color--794b40, #794B40);
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.jynvl5b3k {
  stop-color: var(--svg-color--845a4e, #845A4E);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.kj_uw-bok {
  stop-color: var(--svg-color--875d51, #875D51);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.l2ju9bcgt {
  fill: var(--svg-color--785451, #785451);
  d: path("M10.552 17.701c.325-.003.516.178.57.27a2.2 2.2 0 0 0-.65.566c-.1.125-.278.17-.413.086a.266.266 0 0 1-.079-.39c.257-.328.48-.49.572-.532");
}

.l9og9fbem {
  d: path("m14.787 8.346l.2-1.439a.727.727 0 0 1-.2 1.44");
}

.lgum6kbvi {
  stop-color: var(--svg-color--35232c, #35232C);
}

.lmk5_gb2n {
  stop-color: var(--svg-color--4b77af, #4B77AF);
}

.lq0qk0brb {
  stop-color: var(--svg-color--3a78c3, #3A78C3);
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.m0qbo5zst {
  d: path("M9.236 21.064c.137.575.807 3.427 1.125 4.782c-.573.231-1.39.668-2.067 1.007c-.324.163-.533.496-.443.848a.26.26 0 0 0 .252.195h3.43a.25.25 0 0 0 .25-.252l-.076-7.17c1.787.443 3.937.809 5.747.262c1.2-.362 1.266-1.816 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.m26o0cchb {
  d: path("M11.707 20.477v-.003c1.787.443 3.938.809 5.747.262c1.2-.362 1.266-1.816 1.266-2.875l-7.61.078a3.2 3.2 0 0 0-.701.337z");
}

.m5kggdiwk {
  stop-color: var(--svg-color--3f3035, #3F3035);
  stop-opacity: 0;
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.n03q6iq6j {
  stop-color: var(--svg-color--865f5b, #865F5B);
  stop-opacity: 0;
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
}

.n6csxrxuy {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ng2vn7s5c {
  stop-color: var(--svg-color--744f48, #744F48);
  stop-opacity: 0;
}

.ni_rkbnps {
  stop-color: var(--svg-color--794b40, #794B40);
  stop-opacity: 0;
}

.no3uypbod {
  d: path("M14.73 25.572c-.05-1.837.196-4.492.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.39 1.516c-1.233.125-3.339.522-3.843.648c-.562.14-2.371.085-2.43-2.047");
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.nve29hb1p {
  d: path("M14.276 12.569a1.261 1.261 0 0 1 2.52-.12l.155 2.775l-2.567.153z");
}

.obkbkpctx {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
  stop-opacity: 0;
}

.ofo46gsuq {
  stop-color: var(--svg-color--439ff0, #439FF0);
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.oo0a8g8xe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
}

.oy1ldyvxm {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M13.292 6.829c-.147-.106-.363-.111-.5-.111a.2.2 0 1 1 0-.4h.01c.128 0 .463 0 .723.186a.2.2 0 0 1-.233.325");
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.p26rrpb5e {
  d: path("M12.016 6.892c.039-.801.298-1.187.42-1.3h3.733l.062 3.163c-.866 2.122-3.511 2.213-3.906 1.446s-.354-2.381-.309-3.309");
}

.pnmvm92bz {
  d: path("m10.318 20.4l.656 5.492l.313.125l-.43-5.73a.487.487 0 0 1 .481-.527c.926-.006 3.848 0 4.542 0c.813 0 1.094-.274 1.094-.649c-1.193-.01-4.677-.025-5.664 0s-1.04.862-.992 1.29");
}

.pp9y_ov5j {
  stop-color: var(--svg-color--8d6c64, #8D6C64);
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.ptopy6fga {
  stop-color: var(--svg-color--865f5b, #865F5B);
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.qilpy_bau {
  cx: 12.696px;
  cy: 7.335px;
  rx: 0.064px;
  ry: 0.088px;
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.ra4kqjbah {
  stop-color: var(--svg-color--744f48, #744F48);
}

.rg5t0y_vv {
  d: path("M11.792 7.856a1 1 0 0 0 .258-.457h.18v1.125c-.215.137-.523.115-.614-.09c-.078-.176-.02-.394.176-.578");
}

.ri9ygtemw {
  stop-color: var(--svg-color--2a1528, #2A1528);
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rstbkwref {
  d: path("M13.128 7.686v-.004c0-.32-.137-.58-.307-.58s-.306.26-.306.58v.004z");
}

.skjeal_ka {
  fill: var(--svg-color--785451, #785451);
  d: path("m10.599 17.103l.043.633a4.3 4.3 0 0 0-.603.608a.27.27 0 0 1-.346.059c-.117-.072-.16-.223-.084-.338c.311-.473.794-.844.99-.962");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.swge0f8mu {
  d: path("m12.932 7.686l.005-.072c0-.186-.08-.336-.176-.336c-.097 0-.176.15-.176.336q0 .038.004.072z");
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.u8iayhb4j {
  stop-color: var(--svg-color--514342, #514342);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uk3jx7nau {
  stop-color: var(--svg-color--8a5752, #8A5752);
}

.usazw8ham {
  fill: var(--svg-color--835c5a, #835C5A);
  d: path("m14.685 16.033l-.04-.781l1.891-.125c.047.664.118 1.594-.148 1.984s-.765.858-2.2.945a42 42 0 0 1-3.269.032v-.18h-.672l-.34-.215c-.039-.191.39-.568.79-.71c1.254-.45 2.96-.821 3.988-.95");
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.x4tqf8rmd {
  stop-color: var(--svg-color--3f3035, #3F3035);
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xtp18r_3e {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M14.73 25.572c-.05-1.837.196-4.492.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.39 1.516c-1.233.125-3.339.522-3.843.648c-.562.14-2.371.085-2.43-2.047");
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.y3ztz7b1k {
  stop-color: var(--svg-color--906964, #906964);
  stop-opacity: 0;
}

.z4m0hk31o {
  stop-color: var(--svg-color--774b48, #774B48);
}

.zaqgvq4le {
  d: path("m14.685 16.033l-.04-.781l1.891-.125c.047.664.118 1.594-.148 1.984s-.765.858-2.2.945a42 42 0 0 1-3.269.032v-.18h-.672l-.34-.215c-.039-.191.39-.568.79-.71c1.254-.45 2.96-.821 3.988-.95");
}

</style>
