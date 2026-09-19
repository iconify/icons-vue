<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wvqfxub_f"/><path fill="url(#iQzZczc)" class="k-qshvbme"/><path fill="url(#iMOzZte)" class="k-qshvbme"/><g filter="url(#i8eUUek)"><path fill="url(#il8Nr5c)" class="p_ekaeb2t"/><path fill="url(#iXTeVab)" class="p_ekaeb2t"/><path fill="url(#ivFIFQi)" class="p_ekaeb2t"/><path fill="url(#ijYV71b)" class="p_ekaeb2t"/></g><g filter="url(#i1EAVzc)"><path fill="url(#ibfMZed)" class="ngqft0b-k"/><path fill="url(#iAoHP6b)" class="ngqft0b-k"/><path fill="url(#id2Wnqb)" class="ngqft0b-k"/><path fill="url(#iIJx6So)" class="ngqft0b-k"/></g><path fill="url(#im3UZke)" class="zktn1-b2b"/><path fill="url(#iSKr02d)" class="zktn1-b2b"/><path fill="url(#iZRV6Gb)" class="zktn1-b2b"/><path clip-rule="evenodd" class="aixotgo4i"/><g filter="url(#i2aHfrd)"><path clip-rule="evenodd" class="zoge-nbaf"/></g><path class="w83r0f2le"/><path fill="url(#ifzXAdd)" class="ycfufmugz"/><path fill="url(#ikjvzDd)" class="m12ek8bts"/><ellipse fill="url(#ihScDWc)" transform="scale(-1 1)rotate(74.61 -11.72 -.058)" class="l--rvobkj"/><g filter="url(#iYtmSrn)"><path fill="url(#iRv5LoB)" class="t48szj8gj"/></g><g filter="url(#i2XzAkd)"><path fill="url(#iGoA0ac)" class="b_ap7obfg"/><path fill="url(#i7SEV7d)" class="b_ap7obfg"/></g><g filter="url(#i7AfiCQ)"><path class="g3dg0uy4i"/><path fill="url(#izVqypd)" class="p1xc_s5ui"/></g><g filter="url(#i7EWaje)"><path class="ib2fasbto"/><path fill="url(#iwaJyYk)" class="n81j8n7lw"/><path fill="url(#i3eb7xd)" class="n81j8n7lw"/></g><g filter="url(#iMjX9ec)"><circle fill="url(#ip9rMyp)" class="w4j1rwimw"/><circle fill="url(#iC7CtZc)" class="w4j1rwimw"/></g><g filter="url(#iQ3TyWb)"><path fill="url(#ic26lMd)" clip-rule="evenodd" class="m6-lx_btx"/></g><rect fill="url(#i9HZAie)" transform="scale(-1 1)rotate(45 -41.285 -13.071)" class="hrxlqmt6c"/><rect fill="url(#iwL7NEd)" transform="scale(-1 1)rotate(45 -41.285 -13.071)" class="hrxlqmt6c"/><rect fill="url(#i0csxTc)" transform="scale(-1 1)rotate(45 -41.285 -13.071)" class="hrxlqmt6c"/><rect transform="rotate(45 11.78 25.365)" class="wk7aj4b8h"/><rect fill="url(#ivDRlkc)" transform="rotate(45 11.78 25.365)" class="xhze1z22e"/><rect fill="url(#iDCRcnb)" transform="rotate(45 11.78 25.365)" class="xhze1z22e"/><g filter="url(#ivtALud)"><path fill="url(#iumu4Ge)" class="kmqnmom3j"/></g><path fill="url(#iXA0kQP)" class="kmqnmom3j"/><path fill="url(#iLhwNvc)" class="kmqnmom3j"/><g filter="url(#iOoW3Hb)"><rect fill="url(#iPbwL2c)" class="bjkp6sbto"/><rect fill="url(#if26uQb)" class="bjkp6sbto"/></g><rect fill="url(#i6MJ9zd)" class="bjkp6sbto"/><g filter="url(#iplbYLe)"><path stroke="url(#iYwOZ2b)" class="ajt_jjb6d"/></g><g filter="url(#ig1VCEc)"><path stroke="url(#iIyy4Pe)" class="md_0teoeo"/></g><path fill="url(#iFR61Pb)" class="yu-p9ubeb"/><path fill="url(#ile6U5d)" class="yu-p9ubeb"/><defs><radialGradient id="iQzZczc" cx="0" cy="0" r="1" gradientTransform="rotate(101.587 .839 9.745)scale(.68058 .96066)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="iMOzZte" cx="0" cy="0" r="1" gradientTransform="matrix(-.18357 -.3509 .5266 -.2755 10.532 11.526)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iXTeVab" cx="0" cy="0" r="1" gradientTransform="rotate(-53.18 17.282 .006)scale(1.06144 1.29411)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="ivFIFQi" cx="0" cy="0" r="1" gradientTransform="rotate(-140 7.386 4.111)scale(6.51587 2.53177)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="ijYV71b" cx="0" cy="0" r="1" gradientTransform="matrix(.37586 .31539 -.49185 .58617 8.635 11.884)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="ibfMZed" cx="0" cy="0" r="1" gradientTransform="rotate(168.984 2.751 6.448)scale(3.88926 5.91238)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="iAoHP6b" cx="0" cy="0" r="1" gradientTransform="rotate(166.088 2.99 4.855)scale(1.86588 3.00185)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="id2Wnqb" cx="0" cy="0" r="1" gradientTransform="rotate(-34.167 29.54 -2.269)scale(.6834 .33578)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="iIJx6So" cx="0" cy="0" r="1" gradientTransform="matrix(-.92205 .68665 -1.8398 -2.47053 6.509 13.136)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="im3UZke" cx="0" cy="0" r="1" gradientTransform="matrix(-.78958 .5288 -.2581 -.38538 6.989 13.526)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iSKr02d" cx="0" cy="0" r="1" gradientTransform="rotate(50.843 -10.668 13.677)scale(1.50878 1.57222)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="ifzXAdd" cx="0" cy="0" r="1" gradientTransform="rotate(130 1.74 7.886)scale(.34346 .66728)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ikjvzDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20185 .24055 -.52057 -.4368 9.056 11.477)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iGoA0ac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.09375 .88867 0 20.8 15.15)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ydmmxd7qb"/><stop offset="1" class="tr05emzlm"/></radialGradient><radialGradient id="i7SEV7d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49998 -3.09376 1.67378 -.81152 23.518 14.713)" gradientUnits="userSpaceOnUse"><stop class="mh-0s225o"/><stop offset="1" class="f20gqhbag"/></radialGradient><radialGradient id="izVqypd" cx="0" cy="0" r="1" gradientTransform="rotate(-45.372 16.753 -19.193)scale(6.80605 3.84932)" gradientUnits="userSpaceOnUse"><stop class="xy0op_eyz"/><stop offset="1" class="p53pr-blg"/></radialGradient><radialGradient id="iwaJyYk" cx="0" cy="0" r="1" gradientTransform="rotate(-150.994 14.699 4.713)scale(3.60894 4.34333)" gradientUnits="userSpaceOnUse"><stop class="v7qdu5boj"/><stop offset="1" class="kdd3vfboh"/></radialGradient><radialGradient id="i3eb7xd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 2.625 -1.48498 .60106 19.487 13.838)" gradientUnits="userSpaceOnUse"><stop class="xwt5g5sto"/><stop offset="1" class="x484pmbxx"/></radialGradient><radialGradient id="ip9rMyp" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90038 -2.5625 2.1013 -1.55835 20.749 15.874)" gradientUnits="userSpaceOnUse"><stop class="nmlj7qb8u"/><stop offset="1" class="wijlc3r_o"/></radialGradient><radialGradient id="iC7CtZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -2.34375 2.00586 1.12328 16.843 16.405)" gradientUnits="userSpaceOnUse"><stop class="n35yqc9wi"/><stop offset="1" class="e9nymn0gr"/></radialGradient><radialGradient id="ic26lMd" cx="0" cy="0" r="1" gradientTransform="rotate(-138.668 11.43 4.378)scale(4.20282 3.66642)" gradientUnits="userSpaceOnUse"><stop class="fgfvt8_za"/><stop offset="1" class="kb1q69u9p"/></radialGradient><radialGradient id="iwL7NEd" cx="0" cy="0" r="1" gradientTransform="rotate(79.16 -.565 1.44)scale(1.58615 1.72717)" gradientUnits="userSpaceOnUse"><stop class="lkqdv0bwp"/><stop offset="1" class="vou8iltko"/></radialGradient><radialGradient id="i0csxTc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.442 2.4 1.929)scale(1.40065 .72809)" gradientUnits="userSpaceOnUse"><stop class="go679fbfb"/><stop offset="1" class="jo92-ub-i"/></radialGradient><radialGradient id="iDCRcnb" cx="0" cy="0" r="1" gradientTransform="rotate(-47.663 40.377 1.502)scale(.6726 1.0441)" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></radialGradient><radialGradient id="iumu4Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-15.56247 -.06247 .03888 -9.68481 25.987 22.307)" gradientUnits="userSpaceOnUse"><stop class="vn7ncpb8d"/><stop offset="1" class="htcu-gvqd"/></radialGradient><radialGradient id="iXA0kQP" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -39.1562 0 17.112 19.37)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="mh1kw6b0u"/><stop offset="1" class="mg_zulb9j"/></radialGradient><radialGradient id="iPbwL2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25 -15.4957 0 25.237 16.65)" gradientUnits="userSpaceOnUse"><stop class="ypx_bsb1m"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="iYwOZ2b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71874 10.18756 -7.15636 -4.71965 28.768 3.62)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="iIyy4Pe" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -3.53125 2.69792 1.14602 19.536 6.572)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="iFR61Pb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53418 0 0 -3.55867 20.643 8.611)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="yi5996bix"/><stop offset=".717" class="wvcdyrpfm"/></radialGradient><filter id="i8eUUek" width="7.789" height="6.596" x="3.985" y="9.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.619608 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24060"/></filter><filter id="i1EAVzc" width="5.592" height="8.621" x="2.467" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24060"/></filter><filter id="i2aHfrd" width=".814" height="1.199" x="7.143" y="10.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24060"/></filter><filter id="iYtmSrn" width="3.831" height="3.046" x="2.739" y="12.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24060" stdDeviation=".25"/></filter><filter id="i2XzAkd" width="7.367" height="4.959" x="17.409" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.662745 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24060"/></filter><filter id="i7AfiCQ" width="9.125" height="15.5" x="17.925" y="1.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24060"/></filter><filter id="i7EWaje" width="14.805" height="6.438" x="11.175" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.678431 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24060"/></filter><filter id="iMjX9ec" width="5.582" height="5.582" x="16.058" y="13.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24060" stdDeviation=".25"/></filter><filter id="iQ3TyWb" width="6.341" height="6.485" x="11.284" y="12.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24060" stdDeviation=".25"/></filter><filter id="ivtALud" width="28.578" height="11" x="3.768" y="16.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="3" dy="-1"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24060"/></filter><filter id="iOoW3Hb" width="28.344" height="2.496" x="2.659" y="15.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.698039 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24060"/></filter><filter id="iplbYLe" width="5.047" height="14.518" x="21.784" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24060" stdDeviation=".25"/></filter><filter id="ig1VCEc" width="2.999" height="4.468" x="17.974" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24060" stdDeviation=".25"/></filter><linearGradient id="il8Nr5c" x1="7.887" x2="10.363" y1="14.135" y2="11.52" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="iZRV6Gb" x1="7.099" x2="6.99" y1="13.529" y2="13.681" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="ihScDWc" x1="-.009" x2=".225" y1=".062" y2=".139" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iRv5LoB" x1="5.616" x2="2.468" y1="14.382" y2="12.468" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><linearGradient id="i9HZAie" x1="1.641" x2="-.116" y1="2.961" y2="3.171" gradientUnits="userSpaceOnUse"><stop class="t7wbu9b2k"/><stop offset="1" class="t9935ox4b"/></linearGradient><linearGradient id="ivDRlkc" x1="11.466" x2="13.012" y1="28.867" y2="28.624" gradientUnits="userSpaceOnUse"><stop class="gbuoa-pfp"/><stop offset="1" class="h8mgf7b3a"/></linearGradient><linearGradient id="iLhwNvc" x1="16.558" x2="16.558" y1="17.807" y2="19.213" gradientUnits="userSpaceOnUse"><stop class="nihdd8-bi"/><stop offset="1" class="x6h_eubpf"/></linearGradient><linearGradient id="if26uQb" x1="2.862" x2="12.112" y1="17.244" y2="17.244" gradientUnits="userSpaceOnUse"><stop class="d673tl90q"/><stop offset="1" class="f-q8xrbdi"/></linearGradient><linearGradient id="i6MJ9zd" x1="17.925" x2="17.925" y1="18.154" y2="17.619" gradientUnits="userSpaceOnUse"><stop class="b0b_4h8fx"/><stop offset="1" class="vngbibvro"/></linearGradient><linearGradient id="ile6U5d" x1="19.409" x2="19.409" y1="8.611" y2="8.104" gradientUnits="userSpaceOnUse"><stop class="dcrtohb5r"/><stop offset="1" class="k3-gog70w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-taking-bath-light" /></template>
<style>
.aixotgo4i {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M9.614 12.99a.155.155 0 0 0 .171.14c.417-.04.753-.323.852-.42a.157.157 0 1 0-.219-.225c-.085.083-.355.303-.663.333a.157.157 0 0 0-.141.171");
}

.ajt_jjb6d {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M22.3 2.666c1.218-.052 3.656.94 3.656 3.766v9.375");
}

.b_ap7obfg {
  d: path("M18.499 13.578a2.288 2.288 0 0 1 4.216-.309l1.811 3.6H17.41z");
}

.b0b_4h8fx {
  stop-color: var(--svg-color--b1a1c2, #B1A1C2);
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bjkp6sbto {
  width: 27.844px;
  height: 2.246px;
  x: 2.659px;
  y: 15.908px;
  rx: 1.123px;
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.d673tl90q {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
}

.dcrtohb5r {
  stop-color: var(--svg-color--807f86, #807F86);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e9nymn0gr {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
  stop-opacity: 0;
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.f-q8xrbdi {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
  stop-opacity: 0;
}

.f20gqhbag {
  stop-color: var(--svg-color--f3cfbb, #F3CFBB);
  stop-opacity: 0;
}

.fgfvt8_za {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
}

.ft5dv1b6b {
  fill: none;
}

.g3dg0uy4i {
  fill: var(--svg-color--adadad, #ADADAD);
  d: path("M24.95 6.182v10.937h1.6V6.182a4.313 4.313 0 0 0-8.625 0v1.03h1.6v-1.03a2.712 2.712 0 1 1 5.425 0");
}

.gbuoa-pfp {
  stop-color: var(--svg-color--807d83, #807D83);
}

.go679fbfb {
  stop-color: var(--svg-color--bebac2, #BEBAC2);
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.h8mgf7b3a {
  stop-color: var(--svg-color--807d83, #807D83);
  stop-opacity: 0;
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hrxlqmt6c {
  width: 1.608px;
  height: 5.132px;
  rx: 0.804px;
}

.htcu-gvqd {
  stop-color: var(--svg-color--c7bdd3, #C7BDD3);
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.ib2fasbto {
  fill: var(--svg-color--4bd1f1, #4BD1F1);
  d: path("M14.393 19.432a3.22 3.22 0 0 0 2.706-1.475a2.5 2.5 0 0 0 1.658.615c.659 0 1.256-.245 1.686-.64c.511.615 1.402 1.023 2.415 1.023c1.586 0 2.871-.998 2.871-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.505.247-2.024.647a.107.107 0 0 1-.15-.019c-.431-.546-1.134-.902-1.928-.902c-.531 0-1.022.159-1.417.428a.107.107 0 0 1-.153-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jo92-ub-i {
  stop-color: var(--svg-color--968da0, #968DA0);
  stop-opacity: 0;
}

.k-qshvbme {
  d: path("M9.898 10.807a1.26 1.26 0 0 1-.648-.12l-.145.172l1.082.909c.305-.097.533-.41.409-.663c-.106-.217-.364-.337-.698-.298");
}

.k3-gog70w {
  stop-color: var(--svg-color--8f9198, #8F9198);
  stop-opacity: 0;
}

.kb1q69u9p {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
  stop-opacity: 0;
}

.kdd3vfboh {
  stop-color: var(--svg-color--66ebff, #66EBFF);
  stop-opacity: 0;
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.kmqnmom3j {
  d: path("m5.225 22.376l-1.457-4.57h25.579l-1.478 4.59a7.8 7.8 0 0 1-7.425 5.41h-7.788a7.8 7.8 0 0 1-7.431-5.43");
}

.l--rvobkj {
  rx: 0.081px;
  ry: 0.11px;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lkqdv0bwp {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
}

.m12ek8bts {
  d: path("M8.813 11.768a1 1 0 0 1-.073-.055c-.178-.15-.26-.347-.18-.44c.078-.094.286-.048.464.102q.036.03.067.062z");
}

.m6-lx_btx {
  fill-rule: evenodd;
  d: path("M17.125 15.157a2.32 2.32 0 0 0-.631 2.789a2.742 2.742 0 1 1 .631-2.789");
}

.md_0teoeo {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.224 3.385c-.459.406-1.375 1.612-1.375 3.187");
}

.mg_zulb9j {
  stop-color: var(--svg-color--a887c7, #A887C7);
}

.mh-0s225o {
  stop-color: var(--svg-color--f3cfbb, #F3CFBB);
}

.mh1kw6b0u {
  stop-color: var(--svg-color--bba9cd, #BBA9CD);
  stop-opacity: 0;
}

.n35yqc9wi {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
}

.n81j8n7lw {
  d: path("M14.393 19.432a3.22 3.22 0 0 0 2.706-1.475a2.5 2.5 0 0 0 1.658.615c.659 0 1.256-.245 1.686-.64c.511.615 1.402 1.023 2.415 1.023c1.586 0 2.871-.998 2.871-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.505.247-2.024.647a.107.107 0 0 1-.15-.019c-.431-.546-1.134-.902-1.928-.902c-.531 0-1.022.159-1.417.428a.107.107 0 0 1-.153-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ngqft0b-k {
  d: path("M6.404 8.49a1.29 1.29 0 0 0-1.351.48c-.649.866-.458 1.218-1.24 1.837c-.826.654-1.106 1.083-1.236 1.55l-.003.009c-.128.46-.393 1.413 1.018 2.598c1.3 1.09 2.376 1.203 2.81 1.185l-.021.057c-.107.29.053.582.344.688c.247.091.559-.058.766-.401c.236-.392.402-.686.53-.92a.31.31 0 0 0-.074-.389l-1.07-.898c-.452-.378-.454-.922-.417-1.13c-.453-.406-.548-.729-.465-1.056c.137-.543.33-.586 1.048-1.555c.723-.976.187-1.848-.64-2.054");
}

.nihdd8-bi {
  stop-color: var(--svg-color--a090b0, #A090B0);
}

.nmlj7qb8u {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.p_197nrym {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
  stop-opacity: 0;
}

.p_ekaeb2t {
  d: path("M8.79 10.245c-.803-.61-1.384-.672-1.591-.646L4.185 13.19l2.994 2.615c2.741.88 4.964-1.592 4.545-2.592s-2.006-2.262-2.935-2.968");
}

.p1xc_s5ui {
  d: path("M24.95 6.182v10.937h1.6V6.182a4.313 4.313 0 0 0-8.625 0v1.03h1.6v-1.03a2.712 2.712 0 1 1 5.425 0");
}

.p53pr-blg {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
  stop-opacity: 0;
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t48szj8gj {
  d: path("M4.83 13.065a16 16 0 0 0 1.24 1.494a3.64 3.64 0 0 1-2.551-.618c-.52-.354-.264-1.164.335-1.357c.433-.139.707.114.976.48");
}

.t7wbu9b2k {
  stop-color: var(--svg-color--887a96, #887A96);
}

.t9935ox4b {
  stop-color: var(--svg-color--a9a6ac, #A9A6AC);
}

.tr05emzlm {
  stop-color: var(--svg-color--e2baa5, #E2BAA5);
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v7qdu5boj {
  stop-color: var(--svg-color--66ebff, #66EBFF);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vn7ncpb8d {
  stop-color: var(--svg-color--e1daea, #E1DAEA);
}

.vngbibvro {
  stop-color: var(--svg-color--bbb2c3, #BBB2C3);
  stop-opacity: 0;
}

.vou8iltko {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
  stop-opacity: 0;
}

.w4j1rwimw {
  cx: 18.849px;
  cy: 16.73px;
  r: 2.291px;
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.w83r0f2le {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.144 11.373l-.797.951c-.377-.316-.504-.785-.284-1.048c.22-.262.705-.22 1.081.097");
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wijlc3r_o {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
  stop-opacity: 0;
}

.wk7aj4b8h {
  width: 1.608px;
  height: 5.132px;
  x: 11.78px;
  y: 25.365px;
  fill: var(--svg-color--735f86, #735F86);
  rx: 0.804px;
}

.wvcdyrpfm {
  stop-color: var(--svg-color--929192, #929192);
}

.wvqfxub_f {
  fill: var(--svg-color--c69488, #C69488);
  d: path("m8.298 15.657l1.422-1.034l1.332 1.832L9.63 17.49z");
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.x484pmbxx {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
  stop-opacity: 0;
}

.x6h_eubpf {
  stop-color: var(--svg-color--bcb0c8, #BCB0C8);
  stop-opacity: 0;
}

.xhze1z22e {
  width: 1.608px;
  height: 5.132px;
  x: 11.78px;
  y: 25.365px;
  rx: 0.804px;
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xwt5g5sto {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
}

.xy0op_eyz {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
}

.ycfufmugz {
  d: path("m8.656 11.955l-.004-.003c-.309-.258-.448-.6-.31-.763c.136-.163.497-.086.805.173l.004.003z");
}

.ydmmxd7qb {
  stop-color: var(--svg-color--d8aea4, #D8AEA4);
}

.yi5996bix {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

.yu-p9ubeb {
  d: path("M21.089 8.611c.279 0 .508-.23.456-.504c-.25-1.307-1.37-2.293-2.714-2.293c-1.345 0-2.465.986-2.714 2.293c-.053.274.177.504.456.504z");
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zktn1-b2b {
  d: path("m7.951 14.085l-1.546-.97a.913.913 0 0 0 1.546.97");
}

.zoge-nbaf {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M7.737 11.032a1 1 0 0 1 .16-.22a.188.188 0 0 0-.257-.277a1.3 1.3 0 0 0-.234.316a1.3 1.3 0 0 0-.163.533a.188.188 0 1 0 .376.023a.9.9 0 0 1 .118-.375");
}

</style>
