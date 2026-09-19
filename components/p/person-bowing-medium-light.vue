<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iz1rWRc)" class="xv53ugbum"/><path fill="url(#iSUTjAe)" class="xv53ugbum"/><path fill="url(#idYRWCb)" class="xv53ugbum"/><g filter="url(#inVFLYc)"><path fill="url(#i1beHId)" class="rzi9dvbju"/><path fill="url(#iQ22zFb)" class="rzi9dvbju"/></g><path fill="url(#i6v0Zgd)" class="eeu6inbca"/><path fill="url(#i0Avhkb)" class="eeu6inbca"/><path fill="url(#iwEYVCc)" class="eeu6inbca"/><path fill="url(#isqFEAb)" class="eeu6inbca"/><path fill="url(#i6OlYLc)" class="eeu6inbca"/><g filter="url(#iKlHlWd)"><path fill="url(#iBGprxb)" class="j7w9-zskl"/></g><g filter="url(#iz2gQbV)"><path fill="url(#iSvrt5b)" class="y1-ptub6c"/></g><g filter="url(#id9bGme)"><path fill="url(#iXUpIOd)" class="m7pya-o3n"/></g><path fill="url(#iGMJXge)" class="m1y44xbvu"/><path fill="url(#iSTflpb)" class="ozg57bpfo"/><path fill="url(#ilWhuwc)" class="ozg57bpfo"/><g filter="url(#ip26AZb)"><path class="w8c0xkffw"/><path fill="url(#iWapYae)" class="a0j32cbql"/><path fill="url(#ip3CwWb)" class="a0j32cbql"/><path fill="url(#i5Dz1ab)" class="a0j32cbql"/><path fill="url(#inNI5dc)" class="a0j32cbql"/><path fill="url(#iADwfbP)" class="a0j32cbql"/><path fill="url(#i6osACc)" class="a0j32cbql"/><path fill="url(#isnVr8l)" class="a0j32cbql"/><path fill="url(#iyOUWRc)" class="a0j32cbql"/></g><g filter="url(#iWqpZbf)"><path class="lodrg4b-k"/></g><g filter="url(#iHcFUFv)"><path class="g3-0dj66v"/></g><g filter="url(#iV0W7Qb)"><path class="az5rox7fm"/></g><g filter="url(#i0yhfud)"><path class="kh965ipau"/><path fill="url(#icGVjTd)" class="agn45f-qr"/></g><path fill="url(#iqR4wNe)" class="agn45f-qr"/><g filter="url(#igbrvub)"><path fill="url(#i6tbutq)" class="vo0hy7jmf"/><path fill="url(#inyrJWB)" class="vo0hy7jmf"/><path fill="url(#i9fJpDi)" class="vo0hy7jmf"/></g><g filter="url(#inWg7Ud)"><path fill="url(#icRwjjd)" class="bd16oaboz"/></g><g filter="url(#i0whDcc)"><path fill="url(#iAqOB4d)" class="m3hukqbhy"/><path fill="url(#ijBuFyc)" class="m3hukqbhy"/><path fill="url(#iIMxv2s)" class="m3hukqbhy"/><path fill="url(#iQLKdmb)" class="m3hukqbhy"/></g><path class="l_07gnb6s"/><path fill="url(#iQ0qDxb)" class="fcxd9acml"/><path class="bhadt7bzc"/><g filter="url(#iCRl6Rc)"><path fill="url(#iMFLwGc)" class="gipgusvsh"/></g><g filter="url(#ibjE78O)"><ellipse transform="rotate(-27.914 12.82 20.344)" class="vyz6cvbyg"/><ellipse fill="url(#iKlSHGP)" transform="rotate(-27.914 12.82 20.344)" class="d_mec4bpk"/></g><path class="kk9om7xgx"/><path fill="url(#i5lXdyc)" class="a1-vh2b0k"/><path class="wm8548b1w"/><g filter="url(#iod0sOd)"><path fill="url(#ip65K1s)" class="elymc1jdl"/></g><g filter="url(#iqo7Uvt)"><ellipse transform="rotate(-27.914 18.477 20.344)" class="yyglpzb_k"/><ellipse fill="url(#izsN1se)" transform="rotate(-27.914 18.477 20.344)" class="a1bat5beh"/></g><g filter="url(#i6uT1hg)"><path stroke="url(#iFqwJ3b)" class="byns9c_ix"/></g><g filter="url(#icZBmAd)"><path stroke="url(#iLrPCcc)" class="b9j8hpgdq"/></g><g filter="url(#irn0oLd)"><path class="ju-zp4zoa"/></g><defs><radialGradient id="iz1rWRc" cx="0" cy="0" r="1" gradientTransform="rotate(123.959 7.444 15.84)scale(12.144 23.7823)" gradientUnits="userSpaceOnUse"><stop class="tn5cwfbmj"/><stop offset=".27" class="gur5_240r"/><stop offset="1" class="hke44nb4h"/></radialGradient><radialGradient id="iSUTjAe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01499 4.36558 -4.67954 -3.23182 14.325 23.466)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="ml47xab2p"/><stop offset="1" class="ih_n8tb4s"/></radialGradient><radialGradient id="i1beHId" cx="0" cy="0" r="1" gradientTransform="rotate(-164.898 7.34 12.747)scale(6.67145 7.19435)" gradientUnits="userSpaceOnUse"><stop class="ygnqhzbrp"/><stop offset="1" class="pmiei2beq"/></radialGradient><radialGradient id="i6v0Zgd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.03127 4.7187 -4.36101 -7.42248 28.486 24.4)" gradientUnits="userSpaceOnUse"><stop class="mi21-2olq"/><stop offset=".724" class="wziyle_fm"/></radialGradient><radialGradient id="iwEYVCc" cx="0" cy="0" r="1" gradientTransform="matrix(6.28125 -1.78432 .36961 1.30113 22.267 26.966)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="sludkgsww"/><stop offset="1" class="pjd1wtbcg"/></radialGradient><radialGradient id="isqFEAb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.04861 -4.1627 5.4796 -7.96214 25.049 31.258)" gradientUnits="userSpaceOnUse"><stop offset=".855" class="sd7jkkb7x"/><stop offset="1" class="lt28sz2zp"/></radialGradient><radialGradient id="iGMJXge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79873 0 0 -2.18086 9.75 17.897)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="rpwlwhbbu"/><stop offset="1" class="sd0l_k44p"/></radialGradient><radialGradient id="ilWhuwc" cx="0" cy="0" r="1" gradientTransform="rotate(99.806 3.853 18.382)scale(1.47318)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="p23o1nbek"/><stop offset="1" class="zy0346bxi"/></radialGradient><radialGradient id="iWapYae" cx="0" cy="0" r="1" gradientTransform="matrix(3.03125 5.4375 -6.00358 3.34682 15.31 19.529)" gradientUnits="userSpaceOnUse"><stop class="h1pmuj00y"/><stop offset="1" class="d4_ff5y3o"/></radialGradient><radialGradient id="ip3CwWb" cx="0" cy="0" r="1" gradientTransform="rotate(157.126 6.992 12.566)scale(2.87205 1.88788)" gradientUnits="userSpaceOnUse"><stop class="zvtyeybqs"/><stop offset="1" class="m6rnegsua"/></radialGradient><radialGradient id="i5Dz1ab" cx="0" cy="0" r="1" gradientTransform="matrix(11.4008 0 0 12.5877 11.503 20.238)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="ga26zabsh"/><stop offset="1" class="mopkng_rx"/></radialGradient><radialGradient id="inNI5dc" cx="0" cy="0" r="1" gradientTransform="rotate(-39.188 37.672 -17.065)scale(1.63592 .99685)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="f5yn8-zbj"/><stop offset="1" class="g-n_wbbux"/></radialGradient><radialGradient id="iADwfbP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39098 -1.24648 1.121 -1.25096 12.612 19.814)" gradientUnits="userSpaceOnUse"><stop class="oi4n23iwz"/><stop offset="1" class="nhe2e_3rg"/><stop offset="1" class="xdqbuhbqe"/></radialGradient><radialGradient id="i6osACc" cx="0" cy="0" r="1" gradientTransform="rotate(86.82 -3.012 12.806)scale(8.07057 1.48882)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="fw-l9lbyk"/><stop offset="1" class="wh8qubcwa"/></radialGradient><radialGradient id="isnVr8l" cx="0" cy="0" r="1" gradientTransform="matrix(.14283 11.45751 -11.29472 .1408 16.01 14.509)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="no9e0cx2p"/><stop offset="1" class="rv85g2qqs"/></radialGradient><radialGradient id="iyOUWRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1875 1.73657 0 16.01 26.56)" gradientUnits="userSpaceOnUse"><stop class="wvvf8k7dc"/><stop offset="1" class="mzwp_vm4g"/></radialGradient><radialGradient id="icGVjTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.13784 -1.92952 1.70991 -.12215 16.912 22.667)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="d0pb_nbyd"/><stop offset="1" class="xtn6vnbba"/></radialGradient><radialGradient id="inyrJWB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.10938 .25 0 9.622 30.168)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="n-3a6gp-k"/><stop offset="1" class="hk-j5cbdz"/></radialGradient><radialGradient id="i9fJpDi" cx="0" cy="0" r="1" gradientTransform="rotate(-155.863 10.262 12.795)scale(1.56665 .45501)" gradientUnits="userSpaceOnUse"><stop class="yibm-jbiu"/><stop offset=".609" class="uida46b3y"/></radialGradient><radialGradient id="icRwjjd" cx="0" cy="0" r="1" gradientTransform="rotate(118.993 2.46 19.396)scale(4.6922 7.10654)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="k47z9nben"/><stop offset="1" class="rgv2y6bsf"/></radialGradient><radialGradient id="iAqOB4d" cx="0" cy="0" r="1" gradientTransform="rotate(141.127 9.744 8.75)scale(17.2506 15.7503)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="dzh_o9bpc"/><stop offset=".559" class="jf10kpb1e"/></radialGradient><radialGradient id="ijBuFyc" cx="0" cy="0" r="1" gradientTransform="rotate(164.808 10.607 7.105)scale(15.0251 12.7011)" gradientUnits="userSpaceOnUse"><stop offset=".804" class="mhdgzbc_b"/><stop offset="1" class="e_skh3bah"/></radialGradient><radialGradient id="iIMxv2s" cx="0" cy="0" r="1" gradientTransform="matrix(-4.44243 3.68753 -3.99367 -4.81125 24.252 9.949)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iQLKdmb" cx="0" cy="0" r="1" gradientTransform="rotate(58.911 .753 16.324)scale(3.21125 2.80211)" gradientUnits="userSpaceOnUse"><stop class="n9hcsjz_n"/><stop offset="1" class="ts3o0lbin"/></radialGradient><radialGradient id="iQ0qDxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 13.173 20.468)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dggggwbdc"/></radialGradient><radialGradient id="iKlSHGP" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 12.802 20.753)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5lXdyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 18.83 20.468)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dggggwbdc"/></radialGradient><radialGradient id="izsN1se" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 18.459 20.752)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="inVFLYc" width="11" height="6.1" x="2" y="23.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.478431 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/></filter><filter id="iKlHlWd" width="3.2" height="3.2" x="14.4" y="1.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4045" result="effect2_innerShadow_4002_4045"/></filter><filter id="iz2gQbV" width="3.323" height="3.322" x="7.78" y="2.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4045" result="effect2_innerShadow_4002_4045"/></filter><filter id="id9bGme" width="3.315" height="3.322" x="20.9" y="2.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4045" result="effect2_innerShadow_4002_4045"/></filter><filter id="ip26AZb" width="12.65" height="11.707" x="9.685" y="14.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.466667 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/></filter><filter id="iWqpZbf" width="2.836" height="1.386" x="11.256" y="17.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.262745 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/></filter><filter id="iHcFUFv" width="2.836" height="1.386" x="17.908" y="17.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.25098 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/></filter><filter id="iV0W7Qb" width="3.344" height="4.294" x="14.145" y="20.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4045" stdDeviation=".25"/></filter><filter id="i0yhfud" width="2.445" height="3.473" x="14.828" y="20.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.45098 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/></filter><filter id="igbrvub" width="7" height="3.5" x="9" y="26.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.509804 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/></filter><filter id="inWg7Ud" width="7" height="3.6" x="16.5" y="26.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.443137 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/></filter><filter id="i0whDcc" width="17" height="12.5" x="7.752" y="5.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.8 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.854902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4045" result="effect2_innerShadow_4002_4045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.639216 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_4045" result="effect3_innerShadow_4002_4045"/></filter><filter id="iCRl6Rc" width="1.161" height="1.231" x="13.267" y="19.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4045" stdDeviation=".1"/></filter><filter id="ibjE78O" width="1.125" height=".855" x="12.258" y="19.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4045" stdDeviation=".05"/></filter><filter id="iod0sOd" width="1.161" height="1.231" x="18.924" y="19.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4045" stdDeviation=".1"/></filter><filter id="iqo7Uvt" width="1.125" height=".855" x="17.914" y="19.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4045" stdDeviation=".05"/></filter><filter id="i6uT1hg" width="2.906" height="1.276" x="17.907" y="17.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4045" stdDeviation=".125"/></filter><filter id="icZBmAd" width="2.906" height="1.276" x="11.221" y="17.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4045" stdDeviation=".125"/></filter><filter id="irn0oLd" width="5.315" height="2.887" x="17.782" y="26.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4045" stdDeviation=".25"/></filter><linearGradient id="idYRWCb" x1="2.95" x2="7.199" y1="23.466" y2="24.783" gradientUnits="userSpaceOnUse"><stop class="zsvzg4bjp"/><stop offset="1" class="t727h725g"/></linearGradient><linearGradient id="iQ22zFb" x1="7.19" x2="7.19" y1="30.185" y2="27.24" gradientUnits="userSpaceOnUse"><stop class="y8gz67bnb"/><stop offset="1" class="jiyavqyhw"/></linearGradient><linearGradient id="i0Avhkb" x1="24.5" x2="24.5" y1="30.01" y2="29.088" gradientUnits="userSpaceOnUse"><stop class="dcio5xd0n"/><stop offset="1" class="mw21cz39d"/></linearGradient><linearGradient id="i6OlYLc" x1="23.044" x2="23.184" y1="24.793" y2="25.215" gradientUnits="userSpaceOnUse"><stop class="wfpeklbwv"/><stop offset="1" class="v6e6fkb_o"/></linearGradient><linearGradient id="iBGprxb" x1="17.5" x2="14.905" y1="2.465" y2="4.966" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="iSvrt5b" x1="11.003" x2="8.302" y1="3.365" y2="5.969" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="iXUpIOd" x1="24.115" x2="21.414" y1="3.364" y2="5.961" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="iSTflpb" x1="21.767" x2="23.954" y1="19.463" y2="16.463" gradientUnits="userSpaceOnUse"><stop class="dfnssgbia"/><stop offset="1" class="fpabekwjz"/></linearGradient><linearGradient id="iqR4wNe" x1="16" x2="16" y1="20.807" y2="23.906" gradientUnits="userSpaceOnUse"><stop class="xtq7qfvqy"/><stop offset=".363" class="k_53o757o"/></linearGradient><linearGradient id="i6tbutq" x1="13.404" x2="11.869" y1="27.311" y2="31.01" gradientUnits="userSpaceOnUse"><stop offset=".123" class="yk0j13buw"/><stop offset=".672" class="l1p0x5phq"/></linearGradient><linearGradient id="iMFLwGc" x1="14.138" x2="13.731" y1="20.538" y2="20.789" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ip65K1s" x1="19.794" x2="19.387" y1="20.538" y2="20.789" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFqwJ3b" x1="20.338" x2="18.282" y1="18.092" y2="17.75" gradientUnits="userSpaceOnUse"><stop offset=".515" class="otlf56b8v"/><stop offset="1" class="reguh8bwq"/></linearGradient><linearGradient id="iLrPCcc" x1="11.697" x2="13.752" y1="18.092" y2="17.75" gradientUnits="userSpaceOnUse"><stop offset=".2" class="reguh8bwq"/><stop offset=".598" class="otlf56b8v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bowing-medium-light" /></template>
<style>
.a0j32cbql {
  d: path("M9.693 17.757c-.15-2.288 1.778-3.248 4.098-3.248h1.713c.32.03.59.231.711.534a3.1 3.1 0 0 0 2.835 1.832h1.563q.208.008.412.01c.754.008 1.4.016 1.3.8l-.062.774h.002L22 21.666s-.44 4.3-5.97 4.3s-6.03-4.3-6.03-4.3l-.286-3.651l-.01-.126l-.003-.03z");
}

.a1-vh2b0k {
  d: path("M18.827 19.849a1.158 1.158 0 0 0-1.116 1.463h2.237q.04-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.a1bat5beh {
  cx: 18.477px;
  cy: 20.344px;
  rx: 0.506px;
  ry: 0.256px;
}

.agn45f-qr {
  d: path("m15.52 20.886l-.66 2.14c-.14.44.19.88.65.88h.98c.46 0 .79-.45.65-.88l-.66-2.14c-.15-.47-.82-.47-.96 0");
}

.az5rox7fm {
  fill: var(--svg-color--be7572, #BE7572);
  d: path("m15.44 21.15l-.753 2.045c-.16.42.15.862.61.883l.98.045c.459.02.808-.4.688-.824l-.565-2.106c-.13-.462-.799-.493-.96-.043");
}

.b9j8hpgdq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.752 17.76c-.349-.036-1.484 0-2.156.516");
}

.bd16oaboz {
  d: path("M21.356 26.466c-.244 0-.477.051-.691.153l-3.708 1.766a.82.82 0 0 0-.457.734c0 .45.34.847.769.847h5.721l.01-1.765c.01-.949-.73-1.724-1.645-1.735");
}

.bhadt7bzc {
  fill: var(--svg-color--000, #000);
  d: path("M13.833 21.007a.66.66 0 0 0-.663-.663a.66.66 0 0 0-.59.968h1.174a.66.66 0 0 0 .08-.305");
}

.byns9c_ix {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.283 17.76c.348-.036 1.484 0 2.156.516");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cy-darb1h {
  stop-color: var(--svg-color--3a91ce, #3A91CE);
}

.d_mec4bpk {
  cx: 12.821px;
  cy: 20.344px;
  rx: 0.506px;
  ry: 0.256px;
}

.d0pb_nbyd {
  stop-color: var(--svg-color--e2a998, #E2A998);
}

.d4_ff5y3o {
  stop-color: var(--svg-color--c07e82, #C07E82);
  stop-opacity: 0;
}

.dcio5xd0n {
  stop-color: var(--svg-color--eb5b6d, #EB5B6D);
}

.dfnssgbia {
  stop-color: var(--svg-color--e49d82, #E49D82);
}

.dggggwbdc {
  stop-color: var(--svg-color--6a4c45, #6A4C45);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e_skh3bah {
  stop-color: var(--svg-color--f0bf9a, #F0BF9A);
}

.eeu6inbca {
  d: path("M21.026 25.557a3 3 0 0 0-.333.097c-.987.361-1.693 1.268-1.693 2.332c0 .81.405 1.522 1.039 1.98h6.782c1.756 0 3.179-1.356 3.179-3.005s-1.423-2.995-3.189-2.995c-.27 0-.54.04-.79.098c-.114.03-.228.058-.332.097z");
}

.elymc1jdl {
  d: path("M19.884 20.871c0-.374-.304-.624-.386-.7l-.374.363l.23.469z");
}

.f5yn8-zbj {
  stop-color: var(--svg-color--c9817a, #C9817A);
}

.fcxd9acml {
  d: path("M13.17 19.849a1.158 1.158 0 0 0-1.116 1.463h2.237q.041-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.fpabekwjz {
  stop-color: var(--svg-color--fac7a5, #FAC7A5);
}

.ft5dv1b6b {
  fill: none;
}

.fw-l9lbyk {
  stop-color: var(--svg-color--d89a84, #D89A84);
}

.g-n_wbbux {
  stop-color: var(--svg-color--c9817a, #C9817A);
  stop-opacity: 0;
}

.g3-0dj66v {
  fill: var(--svg-color--9c6231, #9C6231);
  d: path("M20.39 18.656c-.07 0-.15-.02-.21-.07c-.01-.01-.77-.57-1.88-.44c-.2.01-.37-.12-.39-.31a.35.35 0 0 1 .31-.39c1.4-.17 2.35.55 2.39.58c.15.12.18.34.06.49c-.07.1-.18.14-.28.14");
}

.ga26zabsh {
  stop-color: var(--svg-color--f3b48e, #F3B48E);
  stop-opacity: 0;
}

.gipgusvsh {
  d: path("M14.228 20.871c0-.374-.304-.624-.387-.7l-.374.363l.23.469z");
}

.gur5_240r {
  stop-color: var(--svg-color--ff802a, #FF802A);
}

.h1pmuj00y {
  stop-color: var(--svg-color--c07e82, #C07E82);
}

.hk-j5cbdz {
  stop-color: var(--svg-color--d29488, #D29488);
  stop-opacity: 0;
}

.hke44nb4h {
  stop-color: var(--svg-color--fb5b1b, #FB5B1B);
}

.ih_n8tb4s {
  stop-color: var(--svg-color--e4380a, #E4380A);
  stop-opacity: 0;
}

.j7w9-zskl {
  d: path("m15.66 4.756l-1.122-2.248a.377.377 0 0 1 .34-.542h2.244c.28 0 .46.291.34.542L16.34 4.756a.38.38 0 0 1-.68 0");
}

.jf10kpb1e {
  stop-color: var(--svg-color--edd197, #EDD197);
}

.jiyavqyhw {
  stop-color: var(--svg-color--fc6028, #FC6028);
  stop-opacity: 0;
}

.ju-zp4zoa {
  fill: var(--svg-color--ffcbac, #FFCBAC);
  d: path("M20.35 27.496c-1.085.562-1.83.828-2.068.89c.188.105.723.095 1.525-.109c.604-.153 1.257-.445 1.787-.398c.423.037.84.784.989 1.117c.022-.276.036-.928-.083-1.328c-.149-.5-.794-.875-2.15-.172");
}

.k_53o757o {
  stop-color: var(--svg-color--c78685, #C78685);
  stop-opacity: 0;
}

.k47z9nben {
  stop-color: var(--svg-color--f8bf98, #F8BF98);
}

.kh965ipau {
  fill: var(--svg-color--ce9287, #CE9287);
  d: path("m15.52 20.886l-.66 2.14c-.14.44.19.88.65.88h.98c.46 0 .79-.45.65-.88l-.66-2.14c-.15-.47-.82-.47-.96 0");
}

.kk9om7xgx {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.027 19.496c-.848 0-1.564.585-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.464");
}

.l_07gnb6s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.902 19.496c-.848 0-1.564.585-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.464");
}

.l1p0x5phq {
  stop-color: var(--svg-color--c6878a, #C6878A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lodrg4b-k {
  fill: var(--svg-color--89562c, #89562C);
  d: path("M11.61 18.656a.35.35 0 0 1-.28-.14a.35.35 0 0 1 .06-.49c.04-.03.99-.75 2.39-.58c.19.02.33.2.31.39s-.19.33-.39.31c-1.11-.13-1.87.43-1.88.44c-.06.05-.14.07-.21.07");
}

.lt28sz2zp {
  stop-color: var(--svg-color--b64101, #B64101);
}

.m1y44xbvu {
  d: path("M9.75 19.716a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.m3hukqbhy {
  d: path("M23.849 11.115a2.97 2.97 0 0 0-1.623-1.34a3.17 3.17 0 0 1-1.733-1.369a2.98 2.98 0 0 0-2.555-1.44c-.41 0-.811.08-1.172.242a1.93 1.93 0 0 1-1.533 0a2.8 2.8 0 0 0-1.162-.242a2.98 2.98 0 0 0-2.524 1.4a3.37 3.37 0 0 1-1.773 1.41a3.02 3.02 0 0 0-1.673 1.43a3.04 3.04 0 0 0 .18 3.122c.22.332.35.715.35 1.117v1.984c0 .574.545 1.037 1.116 1.037l-.043-.577c-.234-2.383 1.723-3.38 4.087-3.38h1.713c.32.03.59.231.711.534a3.1 3.1 0 0 0 2.835 1.832h1.563c.911.04 1.83-.115 1.712.81l-.062.774c.55 0 1.095-.446 1.095-1v-2.024c0-.393.12-.785.35-1.107a2.98 2.98 0 0 0 .14-3.213");
}

.m6rnegsua {
  stop-color: var(--svg-color--eeb39a, #EEB39A);
  stop-opacity: 0;
}

.m7pya-o3n {
  d: path("m21.49 5.946l2.37-.79a.38.38 0 0 0 .15-.62l-1.58-1.58c-.2-.2-.53-.12-.62.15l-.79 2.38c-.1.28.18.56.47.46");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhdgzbc_b {
  stop-color: var(--svg-color--f0bf9a, #F0BF9A);
  stop-opacity: 0;
}

.mi21-2olq {
  stop-color: var(--svg-color--ffa741, #FFA741);
}

.ml47xab2p {
  stop-color: var(--svg-color--e4380a, #E4380A);
}

.mopkng_rx {
  stop-color: var(--svg-color--f3b48e, #F3B48E);
}

.mw21cz39d {
  stop-color: var(--svg-color--ff6836, #FF6836);
  stop-opacity: 0;
}

.mzwp_vm4g {
  stop-color: var(--svg-color--bb6563, #BB6563);
  stop-opacity: 0;
}

.n-3a6gp-k {
  stop-color: var(--svg-color--d29488, #D29488);
}

.n9hcsjz_n {
  stop-color: var(--svg-color--fff6b5, #FFF6B5);
}

.nhe2e_3rg {
  stop-color: var(--svg-color--6f3948, #6F3948);
  stop-opacity: 0;
}

.no9e0cx2p {
  stop-color: var(--svg-color--bf5d49, #BF5D49);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oi4n23iwz {
  stop-color: var(--svg-color--bb7375, #BB7375);
}

.otlf56b8v {
  stop-color: var(--svg-color--9f6942, #9F6942);
}

.ozg57bpfo {
  d: path("M22.25 19.716a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.p23o1nbek {
  stop-color: var(--svg-color--e09977, #E09977);
}

.pjd1wtbcg {
  stop-color: var(--svg-color--ff9d3d, #FF9D3D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmiei2beq {
  stop-color: var(--svg-color--f46a2e, #F46A2E);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.reguh8bwq {
  stop-color: var(--svg-color--9f6942, #9F6942);
  stop-opacity: 0;
}

.rgv2y6bsf {
  stop-color: var(--svg-color--c48088, #C48088);
}

.rpwlwhbbu {
  stop-color: var(--svg-color--c37564, #C37564);
}

.rv85g2qqs {
  stop-color: var(--svg-color--bf5d49, #BF5D49);
}

.rzi9dvbju {
  d: path("M10.975 25.557c.114.029.228.058.332.097c.987.361 1.693 1.268 1.693 2.332c0 .81-.405 1.522-1.039 1.98H5.178C3.423 29.966 2 28.61 2 26.961s1.423-2.995 3.189-2.995c.27 0 .54.04.79.098c.114.03.228.058.332.097z");
}

.sd0l_k44p {
  stop-color: var(--svg-color--dc9b83, #DC9B83);
}

.sd7jkkb7x {
  stop-color: var(--svg-color--b64101, #B64101);
  stop-opacity: 0;
}

.sludkgsww {
  stop-color: var(--svg-color--ff9d3d, #FF9D3D);
}

.t727h725g {
  stop-color: var(--svg-color--e57544, #E57544);
  stop-opacity: 0;
}

.tn5cwfbmj {
  stop-color: var(--svg-color--ff9c2c, #FF9C2C);
}

.ts3o0lbin {
  stop-color: var(--svg-color--fff6b5, #FFF6B5);
  stop-opacity: 0;
}

.ua70ijcgb {
  stop-color: var(--svg-color--399be2, #399BE2);
}

.uida46b3y {
  stop-color: var(--svg-color--f0bda3, #F0BDA3);
  stop-opacity: 0;
}

.v6e6fkb_o {
  stop-color: var(--svg-color--c95506, #C95506);
  stop-opacity: 0;
}

.vo0hy7jmf {
  d: path("M10.645 26.466c.243 0 .476.051.69.153l3.708 1.766a.82.82 0 0 1 .457.734c0 .45-.34.847-.769.847H9.01L9 28.201c-.01-.949.73-1.724 1.645-1.735");
}

.vyz6cvbyg {
  cx: 12.821px;
  cy: 20.344px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.w8c0xkffw {
  fill: var(--svg-color--e8aa95, #E8AA95);
  d: path("M9.693 17.757c-.15-2.288 1.778-3.248 4.098-3.248h1.713c.32.03.59.231.711.534a3.1 3.1 0 0 0 2.835 1.832h1.563q.208.008.412.01c.754.008 1.4.016 1.3.8l-.062.774h.002L22 21.666s-.44 4.3-5.97 4.3s-6.03-4.3-6.03-4.3l-.286-3.651l-.01-.126l-.003-.03z");
}

.wfpeklbwv {
  stop-color: var(--svg-color--c95506, #C95506);
}

.wh8qubcwa {
  stop-color: var(--svg-color--d89a84, #D89A84);
  stop-opacity: 0;
}

.wm8548b1w {
  fill: var(--svg-color--000, #000);
  d: path("M19.49 21.007a.66.66 0 0 0-.664-.663a.66.66 0 0 0-.59.968h1.175a.66.66 0 0 0 .079-.305");
}

.wvvf8k7dc {
  stop-color: var(--svg-color--bb6563, #BB6563);
}

.wziyle_fm {
  stop-color: var(--svg-color--ff7530, #FF7530);
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xdqbuhbqe {
  stop-color: var(--svg-color--bb7375, #BB7375);
  stop-opacity: 0;
}

.xtn6vnbba {
  stop-color: var(--svg-color--e2a998, #E2A998);
  stop-opacity: 0;
}

.xtq7qfvqy {
  stop-color: var(--svg-color--c78685, #C78685);
}

.xv53ugbum {
  d: path("M26.916 19.155a3.58 3.58 0 0 0-3.305-2.189H8.31c-1.442 0-2.744.86-3.305 2.189L2.25 25.796H7v4.17h18v-4.15l4.75-.017z");
}

.y1-ptub6c {
  d: path("m10.512 5.948l-2.38-.79a.373.373 0 0 1-.14-.62l1.58-1.58c.2-.2.53-.12.62.15l.79 2.38c.1.28-.18.56-.47.46");
}

.y8gz67bnb {
  stop-color: var(--svg-color--e95252, #E95252);
}

.ygnqhzbrp {
  stop-color: var(--svg-color--ff7919, #FF7919);
}

.yibm-jbiu {
  stop-color: var(--svg-color--f0bda3, #F0BDA3);
}

.yk0j13buw {
  stop-color: var(--svg-color--e8b190, #E8B190);
}

.yyglpzb_k {
  cx: 18.477px;
  cy: 20.344px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zsvzg4bjp {
  stop-color: var(--svg-color--e57544, #E57544);
}

.zvtyeybqs {
  stop-color: var(--svg-color--eeb39a, #EEB39A);
}

.zy0346bxi {
  stop-color: var(--svg-color--e3a07d, #E3A07D);
  stop-opacity: 0;
}

</style>
