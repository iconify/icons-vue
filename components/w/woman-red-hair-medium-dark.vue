<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGFAwTc)"><path fill="url(#iuwwdpc)" clip-rule="evenodd" class="iz3g5_x1b"/><path fill="url(#iBE4Jmd)" clip-rule="evenodd" class="iz3g5_x1b"/><path fill="url(#iV2CN6C)" clip-rule="evenodd" class="iz3g5_x1b"/><path fill="url(#iJ8iKIc)" clip-rule="evenodd" class="iz3g5_x1b"/><path fill="url(#i2pIXSb)" clip-rule="evenodd" class="iz3g5_x1b"/><path fill="url(#ii3itRc)" clip-rule="evenodd" class="iz3g5_x1b"/><path fill="url(#ivfEBte)" clip-rule="evenodd" class="iz3g5_x1b"/><path fill="url(#ipEVE0d)" clip-rule="evenodd" class="iz3g5_x1b"/></g><path fill="url(#ibdjzjb)" clip-rule="evenodd" class="ln504xuja"/><path fill="url(#idOHGEV)" clip-rule="evenodd" class="ln504xuja"/><path fill="url(#i7qqJwZ)" clip-rule="evenodd" class="ln504xuja"/><g filter="url(#iWYLFrc)"><path fill="url(#ihiqniI)" class="by9lpf2vs"/></g><g filter="url(#iHbwP5b)"><path fill="url(#i9dHBSb)" class="ix9dvh1gb"/><path fill="url(#iMim8Zv)" class="ix9dvh1gb"/></g><g filter="url(#iCg1SYb)"><path class="kapol-b5z"/><path fill="url(#iAmqh2S)" class="k1f9qge_j"/></g><g filter="url(#itWWeIe)"><path class="zhz9etxxn"/><path fill="url(#iXiWNfb)" class="wdfxpj6wy"/></g><g filter="url(#iNQv4fe)"><path fill="url(#i66LKgz)" class="blrb7jtks"/><path fill="url(#iC7R2cb)" class="blrb7jtks"/><path fill="url(#iNauPCQ)" class="blrb7jtks"/><path fill="url(#i82cqae)" class="blrb7jtks"/><path fill="url(#iNT1R5w)" class="blrb7jtks"/><path fill="url(#ilQHfcd)" class="blrb7jtks"/><path fill="url(#i5WiO9F)" class="blrb7jtks"/><path fill="url(#iiRu2ie)" class="blrb7jtks"/><path fill="url(#i9vVk3d)" class="blrb7jtks"/></g><path fill="url(#iajzZQc)" class="blrb7jtks"/><g filter="url(#iQWvUhd)"><path class="sdrhdtumh"/></g><g filter="url(#ifWSyib)"><path class="zljjlzb3p"/><path fill="url(#iw7Aojb)" class="qp2ms3-6o"/><path fill="url(#itcHLdc)" class="qp2ms3-6o"/><path fill="url(#iyGfNnV)" class="qp2ms3-6o"/><path fill="url(#iMi1VGb)" class="qp2ms3-6o"/></g><path fill="url(#ihZ1oZb)" class="qp2ms3-6o"/><path fill="url(#iC35Vtd)" class="qp2ms3-6o"/><path stroke="url(#iDdnuuM)" class="iqcrlqqte"/><g filter="url(#iiW8Q4c)"><path class="ekaemfb4v"/></g><g filter="url(#iJRmmrI)"><path class="rfny96bya"/></g><g filter="url(#inlh4Eb)"><path class="woyewnbrb"/></g><g filter="url(#ivfsFQb)"><path clip-rule="evenodd" class="ecv0jlsex"/></g><path class="tp6dhxi-l"/><path fill="url(#isY9mme)" class="k314pqbou"/><path class="z00udobwn"/><g filter="url(#iENr6rb)"><path class="upel-jb2w"/><path fill="url(#izG72pd)" class="vccqf4y0u"/></g><g filter="url(#iXdgTUV)"><path fill="url(#irxkNrc)" class="xdjkwfbry"/></g><path class="cnvfw0u-m"/><path fill="url(#iLOEUjc)" class="uv8pytb_z"/><path class="r1al6orcg"/><g filter="url(#iqkDzpd)"><path fill="url(#iPz1qRd)" class="xjryeoqgc"/></g><g filter="url(#iVkA60H)"><ellipse transform="rotate(-27.914 11.596 17.108)" class="swc-f-3dd"/><ellipse fill="url(#idvqbae)" transform="rotate(-27.914 11.596 17.108)" class="ija349bqf"/></g><g filter="url(#ifvdcHb)"><path class="cz6zhnuqk"/></g><g filter="url(#igP3Zsc)"><path class="ykiuw98tn"/></g><g filter="url(#iFeZ62b)"><path class="p14qn2bid"/><path fill="url(#iP16JZb)" class="x50vgv2qu"/><path fill="url(#iDASE6c)" class="x50vgv2qu"/><path fill="url(#iWxf3lc)" class="x50vgv2qu"/><path fill="url(#iNrOUvF)" class="x50vgv2qu"/></g><g filter="url(#iuf3b6d)"><path stroke="url(#ipJveYp)" class="th99e9bnk"/></g><g filter="url(#iYfERUb)"><path class="wxjkowb4t"/></g><g filter="url(#i3Iv7Ne)"><path class="c7100s8-i"/></g><g filter="url(#ifFGskd)"><path fill="url(#i2DCDsc)" class="wnzej3sna"/><path fill="url(#iEmIlrc)" class="wnzej3sna"/></g><defs><radialGradient id="iBE4Jmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.5625 -11.686 0 15.357 21.5)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="d204umqjh"/><stop offset="1" class="x2wzm1pts"/></radialGradient><radialGradient id="iV2CN6C" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.09375 -2.85937 0 7.107 19.438)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="r7yk1hbsh"/><stop offset="1" class="m5o05ncvm"/></radialGradient><radialGradient id="iJ8iKIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 1.1875 -1.20784 1.27141 25.357 21.203)" gradientUnits="userSpaceOnUse"><stop class="dp__ye5xl"/><stop offset="1" class="gkjlbz98a"/></radialGradient><radialGradient id="i2pIXSb" cx="0" cy="0" r="1" gradientTransform="matrix(2 5.8125 -6.49042 2.23326 31.357 22.813)" gradientUnits="userSpaceOnUse"><stop class="l67zd4btt"/><stop offset="1" class="y84axsv8g"/></radialGradient><radialGradient id="ii3itRc" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 5.8125 -5.84354 1.88501 24.107 10.688)" gradientUnits="userSpaceOnUse"><stop class="c65f6x_gr"/><stop offset="1" class="hfih_gbwz"/></radialGradient><radialGradient id="ivfEBte" cx="0" cy="0" r="1" gradientTransform="rotate(-112.011 17.78 -.58)scale(4.75267 2.95369)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="vz8g-eyny"/><stop offset="1" class="zft8-9eiy"/></radialGradient><radialGradient id="ipEVE0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -4.125 2.40626 .72917 7.045 16.5)" gradientUnits="userSpaceOnUse"><stop offset=".374" class="sqlpxdjhr"/><stop offset="1" class="b9hf7jumk"/></radialGradient><radialGradient id="ibdjzjb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 5 -12.92645 6.94796 10.232 3.813)" gradientUnits="userSpaceOnUse"><stop class="vtz65gbjf"/><stop offset="1" class="i0wcpebqt"/></radialGradient><radialGradient id="idOHGEV" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 1.34375 -4.29376 8.5875 2.607 13.844)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jv0bf3wyd"/><stop offset="1" class="rf-gesbub"/></radialGradient><radialGradient id="i7qqJwZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.23437 -2.67187 .95809 -.08404 11.295 10.64)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="vy0k0kb0f"/><stop offset="1" class="scqef813q"/></radialGradient><radialGradient id="i9dHBSb" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 56.213 -45.1)scale(5.09754 6.22385)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iMim8Zv" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 1.375 -.38873 .69354 25.623 15.266)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iAmqh2S" cx="0" cy="0" r="1" gradientTransform="matrix(2.81506 -.2094 .1637 2.2006 24.357 18.61)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iXiWNfb" cx="0" cy="0" r="1" gradientTransform="rotate(-180 3.796 9.2)scale(1.96875)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="i66LKgz" cx="0" cy="0" r="1" gradientTransform="matrix(-12.1254 5.59142 -7.48399 -16.22955 21.5 17.398)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iC7R2cb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06494 1.7887 -1.24562 -2.83076 19.844 18.99)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iNauPCQ" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 26.455 6.386)scale(7.70838 9.7805)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="i82cqae" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39518 13.7467 -17.18312 -2.99393 18.077 16.622)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ermiffb8a"/><stop offset="1" class="d5lrpr21j"/></radialGradient><radialGradient id="iNT1R5w" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.6875 -11.7501 0 15.682 18.125)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="plx9t1yez"/><stop offset="1" class="tcn1mccqj"/></radialGradient><radialGradient id="ilQHfcd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.77 11.262)scale(13.1206 22.5896)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="i5WiO9F" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14551 2.63313 0 20.46 16.618)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iiRu2ie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.44707 2.8045 0 12.298 16.192)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="i9vVk3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62233 6.01598 -4.81378 -1.29814 18.749 12.3)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iajzZQc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3963 0 0 -12.0172 25.67 19.391)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iw7Aojb" cx="0" cy="0" r="1" gradientTransform="matrix(-.84932 -3.81088 1.17448 -.26175 17.632 20.746)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iMi1VGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45312 0 0 -.40625 17.185 21.14)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iC35Vtd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5565 1.75513 -2.1094 -3.07252 16.873 20.031)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="isY9mme" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 20.238 17.287)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="izG72pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.813 17.444)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLOEUjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 12.101 17.287)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="idvqbae" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.494 3.154)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iP16JZb" cx="0" cy="0" r="1" gradientTransform="rotate(114.776 8.711 8.134)scale(8.80534 16.3076)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="xan5-1ewf"/><stop offset="1" class="rd1g7tc9k"/></radialGradient><radialGradient id="iDASE6c" cx="0" cy="0" r="1" gradientTransform="rotate(105.529 8.072 10.648)scale(5.9244 10.9402)" gradientUnits="userSpaceOnUse"><stop class="jlgy9acyk"/><stop offset="1" class="r73csbhtd"/></radialGradient><radialGradient id="iWxf3lc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.036 13.755 2.358)scale(12.9565 11.8348)" gradientUnits="userSpaceOnUse"><stop offset=".9" class="cl60nmbcf"/><stop offset="1" class="d9vojpxpc"/></radialGradient><radialGradient id="iNrOUvF" cx="0" cy="0" r="1" gradientTransform="rotate(-54.573 22.496 -10.378)scale(9.67667 15.3383)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="q43ywbbvh"/><stop offset=".931" class="zqzd-mbvz"/></radialGradient><radialGradient id="iEmIlrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8125 2.90625 -1.5009 -.93605 11 8.801)" gradientUnits="userSpaceOnUse"><stop class="y5tzy9xqj"/><stop offset="1" class="gaoubvbro"/></radialGradient><filter id="iGFAwTc" width="28.25" height="29.25" x="2.17" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.305882 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19469"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.537255 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19469" result="effect2_innerShadow_3987_19469"/></filter><filter id="iWYLFrc" width="6.15" height="6" x="4.434" y="15.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19469"/></filter><filter id="iHbwP5b" width="6" height="6.25" x="22.17" y="15.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19469"/></filter><filter id="iCg1SYb" width="5.005" height="5.005" x="22.667" y="15.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".25"/></filter><filter id="itWWeIe" width="4.505" height="4.505" x="5.217" y="16.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".125"/></filter><filter id="iNQv4fe" width="19" height="20.679" x="6.67" y="9.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19469"/></filter><filter id="iQWvUhd" width="4.5" height="6" x="13.617" y="16.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".25"/></filter><filter id="ifWSyib" width="4" height="5.5" x="14.17" y="16.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".125"/></filter><filter id="iiW8Q4c" width="5.423" height="2.397" x="18.099" y="15.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19469"/></filter><filter id="iJRmmrI" width="5.423" height="2.397" x="8.818" y="15.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19469"/></filter><filter id="inlh4Eb" width="4.4" height="1.861" x="9.07" y="13.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19469"/></filter><filter id="ivfsFQb" width="4.4" height="1.861" x="19.17" y="13.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19469"/></filter><filter id="iENr6rb" width="1.294" height="1.125" x="18.956" y="16.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".05"/></filter><filter id="iXdgTUV" width="1.316" height="1.357" x="20.608" y="16.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".1"/></filter><filter id="iqkDzpd" width="1.493" height="1.594" x="12.325" y="16.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".1"/></filter><filter id="iVkA60H" width="1.529" height="1.141" x="10.831" y="16.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".05"/></filter><filter id="ifvdcHb" width="4.296" height="1.904" x="19.186" y="13.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".2"/></filter><filter id="igP3Zsc" width="4.296" height="1.904" x="9.022" y="13.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".2"/></filter><filter id="iFeZ62b" width="16.82" height="11.348" x="10.068" y="3.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".375"/></filter><filter id="iuf3b6d" width="1.516" height="3.688" x="10.529" y="5.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".1"/></filter><filter id="iYfERUb" width="11.638" height="7.465" x="15.451" y="5.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation="1"/></filter><filter id="i3Iv7Ne" width="6.897" height="16.165" x="1.617" y="6.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".625"/></filter><filter id="ifFGskd" width="6.775" height="10.125" x="4.906" y="5.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19469" stdDeviation=".5"/></filter><linearGradient id="iuwwdpc" x1="24.295" x2="10.42" y1="6.813" y2="23" gradientUnits="userSpaceOnUse"><stop class="i26coab9u"/><stop offset="1" class="yr8yw6b6u"/></linearGradient><linearGradient id="ihiqniI" x1="4.529" x2="6.842" y1="18.563" y2="18.563" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="itcHLdc" x1="14.42" x2="16.17" y1="20.882" y2="20.882" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iyGfNnV" x1="16.17" x2="16.17" y1="22.372" y2="21.234" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="ihZ1oZb" x1="16.316" x2="16.316" y1="22.323" y2="22.063" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iDdnuuM" x1="14.185" x2="15.045" y1="25" y2="23.672" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="irxkNrc" x1="21.688" x2="21.104" y1="17.387" y2="17.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPz1qRd" x1="13.488" x2="12.903" y1="17.387" y2="17.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipJveYp" x1="11.006" x2="11.6" y1="7.217" y2="9.311" gradientUnits="userSpaceOnUse"><stop offset=".538" class="x_d20acpo"/><stop offset="1" class="eo5otrgft"/></linearGradient><linearGradient id="i2DCDsc" x1="11.25" x2="7.063" y1="7.051" y2="11.551" gradientUnits="userSpaceOnUse"><stop class="xa2qcxbqs"/><stop offset="1" class="d-4a9hbql"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-red-hair-medium-dark" /></template>
<style>
.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b9hf7jumk {
  stop-color: var(--svg-color--88311c, #88311C);
  stop-opacity: 0;
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.blrb7jtks {
  d: path("M6.685 16.046h.023l-.02-.495l-.018-.57c.038-1.77 1.07-2.454 1.51-2.683q.044-.015.096-.038q.051-.022.095-.038a4.3 4.3 0 0 0 2.218-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.222 5.729c-.23 5.225-4.31 8.733-9.29 8.733c-4.981 0-9.061-3.508-9.291-8.733z");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.by9lpf2vs {
  d: path("M7.434 21.4a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.c65f6x_gr {
  stop-color: var(--svg-color--df8d6b, #DF8D6B);
}

.c7100s8-i {
  fill: var(--svg-color--d98c73, #D98C73);
  d: path("M5.17 11.157c.094-2.186 1.287-3.27 2.094-3.601c-.76.937-1.118 2.36-1.08 3.644c.04 1.284-.025 2.783-1.512 4.627c-1.432 1.777-.922 4.376-.779 5.394c-2.055-2.747-.46-5.29-.025-5.96s1.19-1.508 1.302-4.104");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl60nmbcf {
  stop-color: var(--svg-color--bc7962, #BC7962);
  stop-opacity: 0;
}

.cnvfw0u-m {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.712 15.89c-1.218 0-2.246.84-2.526 1.975a.51.51 0 0 0 .5.635h4.159a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.cz6zhnuqk {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.786 13.976c.601-.146 2.097-.073 3.096.642");
}

.d-4a9hbql {
  stop-color: var(--svg-color--da7240, #DA7240);
  stop-opacity: 0;
}

.d204umqjh {
  stop-color: var(--svg-color--9f3d3d, #9F3D3D);
}

.d5lrpr21j {
  stop-color: var(--svg-color--793e68, #793E68);
}

.d9vojpxpc {
  stop-color: var(--svg-color--bc7962, #BC7962);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dp__ye5xl {
  stop-color: var(--svg-color--b9583b, #B9583B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecv0jlsex {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m23.127 14.232l-.257.43za.5.5 0 0 1-.514.858l-.008-.005l-.041-.022a5 5 0 0 0-.808-.338c-.542-.173-1.256-.303-2-.171a.5.5 0 1 1-.173-.985c.957-.169 1.843.001 2.476.203a6 6 0 0 1 .981.412q.039.02.06.033l.018.01l.006.003z");
}

.ekaemfb4v {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M18.3 17.339c.494-.87 1.246-1.558 2.865-1.558c.71 0 1.393.197 2 .688c.502.405.435.923.047 1.117l-1.037.592c-1.216-.393-2.56-.446-3.876-.839");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eo5otrgft {
  stop-color: var(--svg-color--9e3623, #9E3623);
  stop-opacity: 0;
}

.ermiffb8a {
  stop-color: var(--svg-color--793e68, #793E68);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.gaoubvbro {
  stop-color: var(--svg-color--c97250, #C97250);
  stop-opacity: 0;
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gkjlbz98a {
  stop-color: var(--svg-color--b9583b, #B9583B);
  stop-opacity: 0;
}

.hfih_gbwz {
  stop-color: var(--svg-color--df8d6b, #DF8D6B);
  stop-opacity: 0;
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.i0wcpebqt {
  stop-color: var(--svg-color--b26d56, #B26D56);
  stop-opacity: 0;
}

.i26coab9u {
  stop-color: var(--svg-color--e3875e, #E3875E);
}

.ija349bqf {
  cx: 11.596px;
  cy: 17.108px;
  rx: 0.726px;
  ry: 0.368px;
}

.iqcrlqqte {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.543 23.142a.34.34 0 0 0-.41.072a.32.32 0 0 0-.034.408a3.65 3.65 0 0 0 3.07 1.678c1.29 0 2.422-.672 3.072-1.678a.33.33 0 0 0-.035-.412a.34.34 0 0 0-.409-.069a5.6 5.6 0 0 1-2.627.637a5.6 5.6 0 0 1-2.627-.636Z");
}

.ix9dvh1gb {
  d: path("M25.17 21.4a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.iz3g5_x1b {
  fill-rule: evenodd;
  d: path("M29.566 21.028a6.05 6.05 0 0 0 .604-2.66c0-.871-.18-1.689-.5-2.434h.009a6 6 0 0 0-.524-.957l-.004-.005a6.04 6.04 0 0 1-.981-3.302v-.02a6.15 6.15 0 0 0-6.151-6.15c-.34 0-.66-.15-.85-.434a6.16 6.16 0 0 0-5-2.566a6.16 6.16 0 0 0-5 2.566a1.05 1.05 0 0 1-.849.434l-.158.002a6.15 6.15 0 0 0-5.992 6.149v.019c0 1.17-.34 2.32-.982 3.302l-.004.007a6.15 6.15 0 0 0-1.014 3.389c0 .962.226 1.849.604 2.66a.96.96 0 0 1 0 .85A6.1 6.1 0 0 0 2.17 24.5c0 3.32 2.679 6 6 6h16c3.32 0 6-2.68 6-6c0-.943-.227-1.83-.604-2.623a.96.96 0 0 1 0-.849M6.708 16.046h-.023l2.235 4.392c.23 5.225 2.269 0 7.25 0s7.152 5.815 7.382.59l1.573-5.684c-.1-2.321-1.237-2.76-1.573-2.76H17.55a7.2 7.2 0 0 1-5.946-3.12a.492.492 0 0 0-.86.095l-.154.362a4.3 4.3 0 0 1-2.218 2.301q-.044.016-.095.038q-.052.023-.096.038c-.44.229-1.472.913-1.51 2.683l.019.57z");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jlgy9acyk {
  stop-color: var(--svg-color--ed804d, #ED804D);
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jv0bf3wyd {
  stop-color: var(--svg-color--d78b73, #D78B73);
}

.k1f9qge_j {
  d: path("M25.17 20.403a2.003 2.003 0 1 0 0-4.006a2.003 2.003 0 0 0 0 4.006");
}

.k314pqbou {
  d: path("M20.242 16.398a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.67-1.663");
}

.kapol-b5z {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M25.17 20.403a2.003 2.003 0 1 0 0-4.006a2.003 2.003 0 0 0 0 4.006");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l67zd4btt {
  stop-color: var(--svg-color--ee8b5f, #EE8B5F);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln504xuja {
  fill-rule: evenodd;
  d: path("M29.566 21.028a6.05 6.05 0 0 0 .604-2.66c0-.871-.18-1.689-.5-2.434h.009a6 6 0 0 0-.524-.957l-.004-.005a6.04 6.04 0 0 1-.981-3.302v-.02a6.15 6.15 0 0 0-6.151-6.15c-.34 0-.66-.15-.85-.434a6.16 6.16 0 0 0-5-2.566a6.16 6.16 0 0 0-5 2.566a1.05 1.05 0 0 1-.849.434l-.158.002a6.15 6.15 0 0 0-5.992 6.149v.019c0 1.17-.34 2.32-.982 3.302l-.004.007a6.15 6.15 0 0 0-1.014 3.389c0 .962.226 1.849.604 2.66a.96.96 0 0 1 0 .85A6.1 6.1 0 0 0 2.17 24.5c0 3.32 2.679 6 6 6h16c3.32 0 6-2.68 6-6c0-.943-.227-1.83-.604-2.623a.96.96 0 0 1 0-.849M6.708 16.046h-.023l2.235 4.392c.23 5.225 2.269 0 7.25 0s7.152 5.815 7.382.59l2.118-5.96c-.1-2.321-1.782-2.484-2.118-2.484H17.55a7.2 7.2 0 0 1-5.946-3.12a.492.492 0 0 0-.86.095l-.154.362a4.3 4.3 0 0 1-2.218 2.301q-.044.016-.095.038q-.052.023-.096.038c-.44.229-1.472.913-1.51 2.683l.019.57z");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m5o05ncvm {
  stop-color: var(--svg-color--8f3727, #8F3727);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p14qn2bid {
  fill: var(--svg-color--d16c37, #D16C37);
  d: path("M15.045 3.875c-2.112-.466-4.008 1.64-4.227 2.422c1.961 6.61 6.923 6.247 11.82 5.703c2.933-.326 3.25 1.01 3.5 1.656c0-7.332-6.234-8.708-11.04-9.77z");
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plx9t1yez {
  stop-color: var(--svg-color--885485, #885485);
  stop-opacity: 0;
}

.q43ywbbvh {
  stop-color: var(--svg-color--e18e6d, #E18E6D);
  stop-opacity: 0;
}

.qp2ms3-6o {
  d: path("m15.457 17.727l-.99 3.169a1.005 1.005 0 0 0 .97 1.304h1.466c.687 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.204-.702-1.426 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1al6orcg {
  fill: var(--svg-color--000, #000);
  d: path("M13.05 18.061a.95.95 0 0 0-.952-.953a.95.95 0 0 0-.953.953c0 .16.038.31.106.439h1.686a.95.95 0 0 0 .114-.439");
}

.r73csbhtd {
  stop-color: var(--svg-color--ed804d, #ED804D);
  stop-opacity: 0;
}

.r7yk1hbsh {
  stop-color: var(--svg-color--8f3727, #8F3727);
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rd1g7tc9k {
  stop-color: var(--svg-color--b14c3d, #B14C3D);
}

.rf-gesbub {
  stop-color: var(--svg-color--d78b73, #D78B73);
  stop-opacity: 0;
}

.rfny96bya {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.04 17.339c-.494-.87-1.246-1.558-2.865-1.558c-.71 0-1.393.197-2 .688c-.502.405-.435.923-.047 1.117l1.037.592c1.215-.393 2.56-.446 3.876-.839");
}

.scqef813q {
  stop-color: var(--svg-color--902b1b, #902B1B);
  stop-opacity: 0;
}

.sdrhdtumh {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.438 17.985l-1.274 3.17a1.005 1.005 0 0 0 .97 1.303H16.6c.688 0 1.173-.662.97-1.304l-.99-3.17c-.212-.701-.92-.701-1.142 0");
}

.sqlpxdjhr {
  stop-color: var(--svg-color--88311c, #88311C);
}

.swc-f-3dd {
  cx: 11.596px;
  cy: 17.108px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tcn1mccqj {
  stop-color: var(--svg-color--885485, #885485);
}

.th99e9bnk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.78 6.203c.043.453.437 2.156 1.015 3.188");
}

.tp6dhxi-l {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.628 15.89c1.217 0 2.246.84 2.526 1.975a.51.51 0 0 1-.5.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.557-2.102");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.upel-jb2w {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.12 16.75c.118.158-.13.351-.412.562c-.281.21-.49.359-.609.2c-.118-.159.014-.458.296-.668s.606-.253.724-.095");
}

.uv8pytb_z {
  d: path("M12.098 16.398a1.664 1.664 0 0 0-1.604 2.102h3.215a1.7 1.7 0 0 0 .06-.439a1.675 1.675 0 0 0-1.671-1.663");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vccqf4y0u {
  d: path("M20.12 16.75c.118.158-.13.351-.412.562c-.281.21-.49.359-.609.2c-.118-.159.014-.458.296-.668s.606-.253.724-.095");
}

.vtz65gbjf {
  stop-color: var(--svg-color--b26d56, #B26D56);
}

.vy0k0kb0f {
  stop-color: var(--svg-color--902b1b, #902B1B);
}

.vz8g-eyny {
  stop-color: var(--svg-color--ad4325, #AD4325);
}

.wdfxpj6wy {
  d: path("M7.47 20.403a2.003 2.003 0 1 0 0-4.006a2.003 2.003 0 0 0 0 4.006");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wnzej3sna {
  d: path("M5.906 11.489c0-3.6 3.104-4.834 4.625-5c.719 2.437-1.297 5.109-2.687 5.796c-1.579.78-1.813 1.86-1.938 2.329z");
}

.woyewnbrb {
  fill: var(--svg-color--352827, #352827);
  d: path("m9.835 15.085l-.008.005a.5.5 0 0 1-.514-.858l.003-.002l.005-.003l.018-.01a3 3 0 0 1 .277-.143c.183-.088.445-.2.764-.302c.634-.202 1.52-.372 2.477-.203a.5.5 0 1 1-.174.985c-.743-.132-1.457-.002-1.999.171a5 5 0 0 0-.849.36");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wxjkowb4t {
  fill: var(--svg-color--fd8c60, #FD8C60);
  d: path("M21.297 7.525h-2.649a1.197 1.197 0 0 0 0 2.395h2.65c1.81 0 3.282.71 3.79 1.064c-1.178-2.953-3.018-3.536-3.79-3.459");
}

.x_d20acpo {
  stop-color: var(--svg-color--bd5422, #BD5422);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x2wzm1pts {
  stop-color: var(--svg-color--9f3d3d, #9F3D3D);
  stop-opacity: 0;
}

.x50vgv2qu {
  d: path("M15.045 3.875c-2.112-.466-4.008 1.64-4.227 2.422c1.961 6.61 6.923 6.247 11.82 5.703c2.933-.326 3.25 1.01 3.5 1.656c0-7.332-6.234-8.708-11.04-9.77z");
}

.xa2qcxbqs {
  stop-color: var(--svg-color--da7240, #DA7240);
}

.xan5-1ewf {
  stop-color: var(--svg-color--b14c3d, #B14C3D);
  stop-opacity: 0;
}

.xdjkwfbry {
  d: path("M21.724 17.842a1.57 1.57 0 0 0-.431-.862l-.485.531l.219.426z");
}

.xjryeoqgc {
  d: path("M13.618 17.866c0-.538-.437-.896-.556-1.005l-.537.52l.33.674z");
}

.y5tzy9xqj {
  stop-color: var(--svg-color--c97250, #C97250);
}

.y84axsv8g {
  stop-color: var(--svg-color--ee8b5f, #EE8B5F);
  stop-opacity: 0;
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ykiuw98tn {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.718 13.976c-.601-.146-2.097-.073-3.096.642");
}

.yr8yw6b6u {
  stop-color: var(--svg-color--b25734, #B25734);
}

.z00udobwn {
  fill: var(--svg-color--000, #000);
  d: path("M19.289 18.061c0-.53.423-.953.953-.953s.953.424.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.439");
}

.zft8-9eiy {
  stop-color: var(--svg-color--ad4325, #AD4325);
  stop-opacity: 0;
}

.zhz9etxxn {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M7.47 20.403a2.003 2.003 0 1 0 0-4.006a2.003 2.003 0 0 0 0 4.006");
}

.zljjlzb3p {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.457 17.727l-.99 3.169a1.005 1.005 0 0 0 .97 1.304h1.466c.687 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.204-.702-1.426 0");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zqzd-mbvz {
  stop-color: var(--svg-color--e18e6d, #E18E6D);
}

</style>
