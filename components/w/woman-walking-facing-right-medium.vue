<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iFfVBDd)" transform="scale(-1 1)rotate(-4.337 79.944 238.653)" class="z8jy9-b3h"/><path fill="url(#iHrMq4c)" class="u535y62dn"/><path fill="url(#iyObfiV)" class="u535y62dn"/><g filter="url(#iZyYexv)"><path fill="url(#iRKtiZd)" class="s60kk4b1z"/><path fill="url(#iRTauoc)" class="s60kk4b1z"/><path fill="url(#iVZTu9D)" class="s60kk4b1z"/><path fill="url(#iSO4C5z)" class="s60kk4b1z"/></g><g filter="url(#iKnIIZc)"><path class="z7bzzjy9o"/><path fill="url(#iJzYskb)" class="by_4dab2a"/></g><path fill="url(#ireXvpd)" class="al7nzibdo"/><path fill="url(#ixUodqd)" class="al7nzibdo"/><path fill="url(#irMdcXc)" class="al7nzibdo"/><g filter="url(#i4NOged)"><path fill="url(#iSD4QoT)" class="ypqlg8byt"/><path fill="url(#iFchPJb)" class="ypqlg8byt"/><path fill="url(#iwDihLN)" class="ypqlg8byt"/></g><g filter="url(#iiQCtLc)"><path class="cib2xzpbp"/><path fill="url(#iomIeSc)" class="evwj63bjo"/><path fill="url(#iFXjklb)" class="evwj63bjo"/><path fill="url(#iiHoqRb)" class="evwj63bjo"/><path fill="url(#idHi0Ob)" class="evwj63bjo"/><path fill="url(#i0srsUd)" class="evwj63bjo"/></g><path fill="url(#izz7xue)" class="wmojipksp"/><path fill="url(#i71uMce)" class="wmojipksp"/><path fill="url(#ixjPjFc)" class="wmojipksp"/><path fill="url(#iawQ0xb)" class="wmojipksp"/><path fill="url(#iiLBmud)" class="wmojipksp"/><path class="pul5hubho"/><path fill="url(#iB2Gpcd)" class="ftcmp1byg"/><path fill="url(#iqwAjyd)" class="ftcmp1byg"/><path fill="url(#irHc5Zc)" class="ftcmp1byg"/><path class="mc_1vg1aj"/><g filter="url(#iDLiIEe)"><path clip-rule="evenodd" class="gojm7xb4x"/><path fill="url(#i9PL5ri)" clip-rule="evenodd" class="fpj5bwf_c"/><path fill="url(#ieN1Tib)" clip-rule="evenodd" class="fpj5bwf_c"/></g><path fill="url(#iW4XZUc)" class="emoo8fk3r"/><path class="wn9le6bdp"/><path fill="url(#inBSsNe)" class="bnjr1accg"/><path fill="url(#icsNHIe)" class="bnjr1accg"/><path fill="url(#i5cvxXK)" class="bnjr1accg"/><path fill="url(#iwg9Gie)" class="bnjr1accg"/><path fill="url(#i0Be9zc)" class="bnjr1accg"/><circle fill="url(#iO9G6Yb)" transform="matrix(-1 0 0 1 11.62 17.491)" class="am9uocbqt"/><g filter="url(#iT3thfc)"><path class="lw1w950ty"/></g><g filter="url(#iNZlWvT)"><path clip-rule="evenodd" class="oph8ub73p"/></g><g filter="url(#iNqAJdd)"><path class="q5s34cckv"/></g><g filter="url(#i3ayaKe)"><path fill="url(#iKIFRdr)" class="aqnagcbco"/><path fill="url(#itgKhHd)" class="aqnagcbco"/><path fill="url(#i7vfRRc)" class="aqnagcbco"/></g><path fill="url(#iX0biIe)" class="z2voyacgl"/><path fill="url(#irWZgze)" class="z2voyacgl"/><path clip-rule="evenodd" class="fntd4jb-t"/><g filter="url(#ixUvtbe)"><path clip-rule="evenodd" class="weayd94jy"/></g><path class="o835mkbbk"/><path fill="url(#ierh8Zb)" class="h2pkht5ud"/><path fill="url(#ioayomb)" class="ne79aobww"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -21.741 -42.44)" class="m1l7k9jve"/><g filter="url(#icU1UDS)"><path fill="url(#ikbB7ud)" class="ic5fefbiv"/></g><g filter="url(#iDOV3Fe)"><path fill="url(#iNdxovc)" class="khewgsbsb"/></g><defs><radialGradient id="iFfVBDd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30831 .72148 -1.24915 -2.26517 1.33 1.557)" gradientUnits="userSpaceOnUse"><stop class="a8teb08ti"/><stop offset=".912" class="cu_980bjg"/></radialGradient><radialGradient id="iHrMq4c" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 9.618 5.768)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="iyObfiV" cx="0" cy="0" r="1" gradientTransform="matrix(.12006 -.29152 .4375 .18018 20.417 6.582)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="iRTauoc" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 17.16 5.561)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="iVZTu9D" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 20.056 6.749)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="iSO4C5z" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 19.228 5.608)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="iJzYskb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53488 -.4317 .92512 -3.28923 20.284 3.326)" gradientUnits="userSpaceOnUse"><stop class="zy9nvz9pf"/><stop offset="1" class="xfcyplbyz"/></radialGradient><radialGradient id="ireXvpd" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 9.119 1.484)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="ixUodqd" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 6.586 9.78)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="iFchPJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 15.047 18.039)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="iwDihLN" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 4.55 12.051)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="iomIeSc" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 13.828 6.002)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iFXjklb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 15.332 16.194)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="idHi0Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 20.027 28.108)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="i0srsUd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 19.707 19.241)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="izz7xue" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 21.16 29.461)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="i71uMce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 24.27 28.523)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="ixjPjFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 20.253 29.757)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="irHc5Zc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 35.171 4.247)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="i9PL5ri" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.07812 .17828 -2.42485 24.306 17.124)" gradientUnits="userSpaceOnUse"><stop class="evse4xbsp"/><stop offset="1" class="kvk1913yc"/></radialGradient><radialGradient id="ieN1Tib" cx="0" cy="0" r="1" gradientTransform="matrix(1.48437 1.71875 -.79818 .68934 19.541 12.624)" gradientUnits="userSpaceOnUse"><stop class="vs59ofb4h"/><stop offset="1" class="h8yojgb3l"/></radialGradient><radialGradient id="inBSsNe" cx="0" cy="0" r="1" gradientTransform="rotate(-88.915 15.97 .231)scale(4.95211 1.34022)" gradientUnits="userSpaceOnUse"><stop class="dkjt4cbcx"/><stop offset="1" class="w9ku-ifwq"/></radialGradient><radialGradient id="icsNHIe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65186 0 0 -15.6875 17.311 14.306)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="p0p0ijbbx"/><stop offset=".967" class="dvcrl_y_s"/></radialGradient><radialGradient id="i5cvxXK" cx="0" cy="0" r="1" gradientTransform="matrix(4.78125 .78125 -1.79108 10.96143 13.936 15.118)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="jx6m9tune"/><stop offset=".931" class="g41565bda"/></radialGradient><radialGradient id="iwg9Gie" cx="0" cy="0" r="1" gradientTransform="matrix(-.51563 1.34375 -3.67742 -1.41111 17.374 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="mwuao6bkl"/><stop offset="1" class="jw-yqmb7v"/></radialGradient><radialGradient id="i0Be9zc" cx="0" cy="0" r="1" gradientTransform="rotate(54.539 -.573 19.4)scale(1.15812 2.04942)" gradientUnits="userSpaceOnUse"><stop class="aflh_2rif"/><stop offset="1" class="ujjvz6nrm"/></radialGradient><radialGradient id="iO9G6Yb" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="h40q0rjti"/><stop offset="1" class="knd8fccgb"/></radialGradient><radialGradient id="itgKhHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0907 .20313 -.4206 -2.25834 17.12 10.352)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="xot8u71lw"/><stop offset="1" class="jjp3z2beb"/></radialGradient><radialGradient id="i7vfRRc" cx="0" cy="0" r="1" gradientTransform="rotate(135.955 4.99 7.887)scale(2.65202 1.5046)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="lz70c3nqo"/><stop offset="1" class="pt5v4qb1w"/></radialGradient><radialGradient id="iX0biIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8373 -.05633 .04465 -.66361 23.996 16.592)" gradientUnits="userSpaceOnUse"><stop class="civdnabwc"/><stop offset="1" class="h68b-xbmi"/></radialGradient><radialGradient id="irWZgze" cx="0" cy="0" r="1" gradientTransform="matrix(.3295 .2729 -.22275 .26895 23.04 16.542)" gradientUnits="userSpaceOnUse"><stop class="oe0g3cb-i"/><stop offset="1" class="i18n49bdr"/></radialGradient><radialGradient id="ierh8Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.523 5.636)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ioayomb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.691 5.657)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iRKtiZd" x1="17.472" x2="20.335" y1="6.304" y2="6.476" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="irMdcXc" x1="17.517" x2="17.369" y1="5.521" y2="5.532" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="iSD4QoT" x1="14.027" x2="11.799" y1="22.898" y2="20.954" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iiHoqRb" x1="16.253" x2="16.253" y1="16.085" y2="16.429" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="iawQ0xb" x1="21.722" x2="21.636" y1="29.632" y2="29.319" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iiLBmud" x1="19.753" x2="20.332" y1="30.007" y2="29.788" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iB2Gpcd" x1="11.144" x2="10.55" y1="27.991" y2="28.163" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iqwAjyd" x1="9.019" x2="9.199" y1="28.065" y2="27.917" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="iW4XZUc" x1="19.3" x2="18.425" y1="12.851" y2="10.46" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset=".787" class="biw5o_cgj"/></linearGradient><linearGradient id="iKIFRdr" x1="15.269" x2="14.16" y1="9.132" y2="12.585" gradientUnits="userSpaceOnUse"><stop offset=".118" class="u1dukib7n"/><stop offset="1" class="mk0srdu2z"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ikbB7ud" x1="19.925" x2="15.3" y1="27.429" y2="17.288" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iNdxovc" x1="9.781" x2="14.092" y1="25.338" y2="19.966" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="iZyYexv" width="4.443" height="5.249" x="15.892" y="3.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.329412 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_725"/></filter><filter id="iKnIIZc" width="6.813" height="7.403" x="13.683" y="1.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.294118 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_725"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.172549 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_725" result="effect2_innerShadow_2_725"/></filter><filter id="i4NOged" width="8.674" height="14.771" x="7.888" y="15.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_725"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_725" result="effect2_innerShadow_2_725"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_725" result="effect3_innerShadow_2_725"/></filter><filter id="iiQCtLc" width="10.972" height="14.104" x="13.646" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_725"/></filter><filter id="iDLiIEe" width="8.438" height="7.859" x="15.777" y="10.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.32549 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_725"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.341176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_725" result="effect2_innerShadow_2_725"/></filter><filter id="iT3thfc" width="5.442" height="5.875" x="12.278" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_725" stdDeviation=".375"/></filter><filter id="iNZlWvT" width="7.59" height="10.511" x="8.519" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.403922 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_725"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.6 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_725" result="effect2_innerShadow_2_725"/></filter><filter id="iNqAJdd" width="6.084" height="9.069" x="8.839" y="9.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_725" stdDeviation=".3"/></filter><filter id="i3ayaKe" width="4.758" height="4.525" x="12.613" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.254902 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_725"/></filter><filter id="ixUvtbe" width="1.013" height=".568" x="18.66" y="4.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_725"/></filter><filter id="icU1UDS" width="6.844" height="12.891" x="14.3" y="16.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_725" stdDeviation=".5"/></filter><filter id="iDOV3Fe" width="6.45" height="8.475" x="8.746" y="18.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_725" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-walking-facing-right-medium" /></template>
<style>
.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.a8teb08ti {
  stop-color: var(--svg-color--593634, #593634);
}

.aflh_2rif {
  stop-color: var(--svg-color--281a4b, #281A4B);
}

.al7nzibdo {
  d: path("m17.614 6.325l-.2-1.439a.727.727 0 0 0 .2 1.44");
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.aqnagcbco {
  d: path("M16.612 11.218a1.355 1.355 0 1 0-1.729-2.088c-.951.692-1.79 1.592-2.27 2.135l2.039 1.914c.308-.32 1.382-1.393 1.96-1.961");
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.biw5o_cgj {
  stop-color: var(--svg-color--816fa6, #816FA6);
}

.bnjr1accg {
  d: path("M16.476 8.612c-.89 0-1.137.215-1.433.407l-1.024 2.597c-.3 1.4-.364 3.636-.36 4.578h4.766c.258-.656.678-2.675.516-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.by_4dab2a {
  d: path("M20.427 3.517c.171-.41-.017-.844-.113-.993c-.367-.672-1.128-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.836-.239-1.867-.13-2.406.84c-.54.968.046 2.058-.086 2.651c-.133.594-.512.653-.653 1.34c-.117.953.473 1.575.996 1.715c.524.14 1.602 0 1.954-.875c.575-1.431.184-2.11.309-2.828c.125-.719.554-.922 1.336-.766c.92.184 1.505-.126 1.734-.671");
}

.cib2xzpbp {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M19.183 18.577c-.383-1.05-.716-2.029-.773-2.383h-4.742c-.1 1.375.144 1.712.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.663-.188-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.civdnabwc {
  stop-color: var(--svg-color--c39883, #C39883);
}

.ckhjb_bgt {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
}

.cl2mlwbhs {
  stop-color: var(--svg-color--4a4b75, #4A4B75);
}

.cnh3p8b3x {
  stop-color: var(--svg-color--817076, #817076);
  stop-opacity: 0;
}

.csaq2_bel {
  stop-color: var(--svg-color--444571, #444571);
  stop-opacity: 0;
}

.cu_980bjg {
  stop-color: var(--svg-color--af867a, #AF867A);
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dkjt4cbcx {
  stop-color: var(--svg-color--7966a4, #7966A4);
}

.dvcrl_y_s {
  stop-color: var(--svg-color--6c5d89, #6C5D89);
}

.emoo8fk3r {
  d: path("M18.785 10.515c-.282-.713-.774-1.224-.985-1.391l.04 4.469l1.785-.836c-.278-.524-.489-1.352-.84-2.242");
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.evse4xbsp {
  stop-color: var(--svg-color--c59983, #C59983);
}

.evwj63bjo {
  d: path("M19.183 18.577c-.383-1.05-.716-2.029-.773-2.383h-4.742c-.1 1.375.144 1.712.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.663-.188-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.ex23x-brg {
  stop-color: var(--svg-color--8c8388, #8C8388);
  stop-opacity: 0;
}

.ezcqmvbni {
  stop-color: var(--svg-color--443a80, #443A80);
}

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
}

.fntd4jb-t {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M19.055 6.77a.125.125 0 0 0 .002.178c.238.233.582.293.692.304a.125.125 0 0 0 .025-.248c-.094-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
}

.fpj5bwf_c {
  fill-rule: evenodd;
  d: path("M22.831 18.406a.85.85 0 0 0 1.13-.433l.19-.427a.755.755 0 0 0-.383-.992c-1.533-.704-4.023-2.149-4.983-5.93l-2.008.524c1.185 4.668 4.29 6.44 6.054 7.258");
}

.ft5dv1b6b {
  fill: none;
}

.ftcmp1byg {
  d: path("m8.965 25.668l1.638.678l-.022.02l.107.355c.217.713.536 1.764.62 2.27c.077.462-.145.768-.35.953c-.094.083-.235.064-.319-.03L7.951 26.92a.25.25 0 0 1 .02-.353l.985-.887z");
}

.fxoxl0blj {
  stop-color: var(--svg-color--8c8393, #8C8393);
  stop-opacity: 0;
}

.g24ahctiy {
  stop-color: var(--svg-color--94899e, #94899E);
  stop-opacity: 0;
}

.g41565bda {
  stop-color: var(--svg-color--8272a4, #8272A4);
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gojm7xb4x {
  fill: var(--svg-color--a17463, #A17463);
  fill-rule: evenodd;
  d: path("M22.831 18.406a.85.85 0 0 0 1.13-.433l.19-.427a.755.755 0 0 0-.383-.992c-1.533-.704-4.023-2.149-4.983-5.93l-2.008.524c1.185 4.668 4.29 6.44 6.054 7.258");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h2pkht5ud {
  d: path("M19.195 5.657v-.004c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.h40q0rjti {
  stop-color: var(--svg-color--a2726b, #A2726B);
}

.h68b-xbmi {
  stop-color: var(--svg-color--986558, #986558);
}

.h8yojgb3l {
  stop-color: var(--svg-color--b68a73, #B68A73);
  stop-opacity: 0;
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.i18n49bdr {
  stop-color: var(--svg-color--9f6b61, #9F6B61);
  stop-opacity: 0;
}

.ic5fefbiv {
  d: path("m18.8 21.194l1.344 6.5l-.36.313l-1.468-6.531L15.3 17.6l.703-.485z");
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.jjp3z2beb {
  stop-color: var(--svg-color--8974b4, #8974B4);
  stop-opacity: 0;
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jw-yqmb7v {
  stop-color: var(--svg-color--6f5797, #6F5797);
  stop-opacity: 0;
}

.jx6m9tune {
  stop-color: var(--svg-color--8272a4, #8272A4);
  stop-opacity: 0;
}

.khewgsbsb {
  d: path("M12.972 21.142L9.496 25.57l.514.199l3.484-3.708a3 3 0 0 0 .761-1.493l.19-1l-.751-.774l-.544 1.993q-.053.196-.178.355");
}

.knd8fccgb {
  stop-color: var(--svg-color--9d6081, #9D6081);
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.kvk1913yc {
  stop-color: var(--svg-color--c59983, #C59983);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l138bfbcs {
  stop-color: var(--svg-color--282955, #282955);
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.lw1w950ty {
  fill: var(--svg-color--442e79, #442E79);
  d: path("M16.764 10.985c.31-.248.178-.39.178-.818c0-.749-.013-.95-.761-.95a1.35 1.35 0 0 0-.883.327c-.95.692-1.79 1.592-2.27 2.135l2.04 1.914a58 58 0 0 0 1.696-2.608");
}

.lz70c3nqo {
  stop-color: var(--svg-color--9075ca, #9075CA);
}

.m_uy2vb_d {
  stop-color: var(--svg-color--695c75, #695C75);
  stop-opacity: 0;
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m3n9jy0fh {
  stop-color: var(--svg-color--63617e, #63617E);
}

.mc_1vg1aj {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M18.795 5.146c.132-.131.35-.161.442-.16l-.303.467c-.147-.008-.303-.143-.139-.307");
}

.mk0srdu2z {
  stop-color: var(--svg-color--7759b2, #7759B2);
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.mwuao6bkl {
  stop-color: var(--svg-color--4d395c, #4D395C);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ne79aobww {
  d: path("m19.39 5.657l-.004-.072c0-.186.08-.336.176-.336c.097 0 .176.15.176.336l-.004.072z");
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.o835mkbbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.8 5.657h-.988c0-.391.221-.709.494-.709s.494.318.494.71");
}

.oe0g3cb-i {
  stop-color: var(--svg-color--a87c71, #A87C71);
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
}

.oph8ub73p {
  fill: var(--svg-color--aa7974, #AA7974);
  fill-rule: evenodd;
  d: path("M10.164 19.238a.614.614 0 0 0 .775-.407c1.215-3.921 3.166-6.29 4.542-7.545c.438-.4.516-1.082.128-1.53c-.346-.401-.944-.472-1.348-.13c-1.626 1.381-3.91 3.976-5.316 8.605a.59.59 0 0 0 .382.73z");
}

.oxce79bcz {
  stop-color: var(--svg-color--282955, #282955);
  stop-opacity: 0;
}

.oxg1n1wjw {
  stop-color: var(--svg-color--5a577e, #5A577E);
}

.p0p0ijbbx {
  stop-color: var(--svg-color--6c5d89, #6C5D89);
  stop-opacity: 0;
}

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pt5v4qb1w {
  stop-color: var(--svg-color--9075ca, #9075CA);
  stop-opacity: 0;
}

.pul5hubho {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m8.965 25.668l1.638.678l-.022.02l.107.355c.217.713.536 1.764.62 2.27c.077.462-.145.768-.35.953c-.094.083-.235.064-.319-.03L7.951 26.92a.25.25 0 0 1 .02-.353l.985-.887z");
}

.q5s34cckv {
  stroke: var(--svg-color--c09887, #C09887);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.124 10.702c-.97.906-3.157 3.219-4.485 7.469");
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rm4aiz5dn {
  stop-color: var(--svg-color--887e8b, #887E8B);
  stop-opacity: 0;
}

.rnrhdzckq {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
  stop-opacity: 0;
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.s60kk4b1z {
  d: path("M20.307 4.863c-.039-.8-.298-1.187-.42-1.3h-3.733l-.062 3.164c.866 2.121 3.511 2.212 3.906 1.445s.354-2.381.309-3.309");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u1dukib7n {
  stop-color: var(--svg-color--8265b5, #8265B5);
}

.u535y62dn {
  d: path("M20.53 5.827a1 1 0 0 1-.257-.457h-.18v1.125c.215.137.522.115.614-.09c.078-.176.02-.394-.176-.578");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ujjvz6nrm {
  stop-color: var(--svg-color--483368, #483368);
  stop-opacity: 0;
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.v5lz4sb9o {
  stop-color: var(--svg-color--695c75, #695C75);
}

.v9kimlbms {
  stop-color: var(--svg-color--94899e, #94899E);
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vs59ofb4h {
  stop-color: var(--svg-color--b68a73, #B68A73);
}

.w9ku-ifwq {
  stop-color: var(--svg-color--7966a4, #7966A4);
  stop-opacity: 0;
}

.weayd94jy {
  fill: var(--svg-color--513a3c, #513A3C);
  fill-rule: evenodd;
  d: path("M19.288 4.624a.7.7 0 0 1 .216-.015a.15.15 0 0 0 .038-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.409.172a.15.15 0 0 0 .179.242c.085-.063.19-.1.289-.12");
}

.wmojipksp {
  d: path("m19.406 28.636l.391 1.285a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.591-.167-1.673-.262-2.306-.317l-.21-.019v-.002z");
}

.wn9le6bdp {
  fill: var(--svg-color--725ca6, #725CA6);
  d: path("M16.476 8.612c-.89 0-1.137.215-1.433.407l-1.024 2.597c-.3 1.4-.364 3.636-.36 4.578h4.766c.258-.656.678-2.675.516-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.x5p6yzbmf {
  stop-color: var(--svg-color--817076, #817076);
}

.xfcyplbyz {
  stop-color: var(--svg-color--654e4b, #654E4B);
  stop-opacity: 0;
}

.xh_da2q2q {
  stop-color: var(--svg-color--60618d, #60618D);
}

.xot8u71lw {
  stop-color: var(--svg-color--8974b4, #8974B4);
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.ypqlg8byt {
  d: path("m12.831 19.96l.891-3.734h1.781c.052.614.152 2.215.29 3.515s-.492 2.032-.766 2.313l-4.446 4.312c.198.662.627 2.025.727 2.625c.077.462-.145.768-.35.953c-.094.083-.235.064-.319-.03L7.952 26.92a.25.25 0 0 1 .018-.353l.986-.887c1.042-1.365 3.191-4.194 3.454-4.594c.18-.276.39-.917.421-1.125");
}

.yvuyjoqpy {
  stop-color: var(--svg-color--47456f, #47456F);
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z2voyacgl {
  d: path("m23.343 16.026l-.496.052a.435.435 0 0 0-.388.403a.38.38 0 0 0 .077.266c.264.33.524.366.721.408c.22.047.676-.191.59-.691a.53.53 0 0 0-.504-.438");
}

.z7bzzjy9o {
  fill: var(--svg-color--52333b, #52333B);
  d: path("M20.427 3.517c.171-.41-.017-.844-.113-.993c-.367-.672-1.128-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.836-.239-1.867-.13-2.406.84c-.54.968.046 2.058-.086 2.651c-.133.594-.512.653-.653 1.34c-.117.953.473 1.575.996 1.715c.524.14 1.602 0 1.954-.875c.575-1.431.184-2.11.309-2.828c.125-.719.554-.922 1.336-.766c.92.184 1.505-.126 1.734-.671");
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.zy9nvz9pf {
  stop-color: var(--svg-color--654e4b, #654E4B);
}

</style>
