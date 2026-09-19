<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iTdFI9b)"><circle fill="url(#iIrJHrb)" class="l95nrybxs"/></g><g filter="url(#i9IeLtd)"><circle fill="url(#i15r5sd)" class="nfhmpfbow"/></g><g filter="url(#ihTQeJb)"><circle fill="url(#iz14K9b)" class="a59tocc-c"/><circle fill="url(#ixYPiXc)" class="a59tocc-c"/></g><g filter="url(#iyOJPEe)"><circle class="yczt3zwsf"/><circle fill="url(#icY7ZHs)" class="zjd0whgav"/><circle fill="url(#ieplpze)" class="zjd0whgav"/></g><g filter="url(#io7Dckb)"><path fill="url(#iePW6JR)" class="i8pk5x4lf"/><path fill="url(#iB9vHWd)" class="i8pk5x4lf"/><path fill="url(#ildss2X)" class="i8pk5x4lf"/><path fill="url(#iz7MKqc)" class="i8pk5x4lf"/><path fill="url(#ipPymdb)" class="i8pk5x4lf"/><path fill="url(#iTsphvE)" class="i8pk5x4lf"/></g><g filter="url(#i84zoKa)"><path class="g8udy2bfd"/><path fill="url(#iby38Uc)" class="tm83ogpeh"/><path fill="url(#iF14r2c)" class="tm83ogpeh"/><path fill="url(#iTjT4pe)" class="tm83ogpeh"/><path fill="url(#iKWNHGe)" class="tm83ogpeh"/><path fill="url(#igvIxYb)" class="tm83ogpeh"/></g><path fill="url(#iiRl7kb)" class="tm83ogpeh"/><path fill="url(#i0YK9Mz)" class="tm83ogpeh"/><g filter="url(#i0kkO8d)"><path class="fgk5p2gyi"/></g><g filter="url(#ic4NKye)"><path class="etm-usb1o"/><path fill="url(#ijGazjl)" class="na9lb6b3a"/><path fill="url(#i3sQSLc)" class="na9lb6b3a"/><path fill="url(#iGgvMuU)" class="na9lb6b3a"/><path fill="url(#iNehz7U)" class="na9lb6b3a"/></g><path fill="url(#iKIWK5c)" class="na9lb6b3a"/><path stroke="url(#iUOC6UK)" class="zh3sjtblp"/><g filter="url(#iL64rVv)"><path class="r49s0uo1k"/></g><g filter="url(#ivCyzFv)"><path class="qmv9bbywi"/></g><path class="ucqn5mg9d"/><path fill="url(#icCcsSc)" class="ocwpl4b1u"/><path class="hhh8z8ibj"/><g filter="url(#ikdYbxe)"><path class="wq3eyabtb"/><path fill="url(#iWeyuob)" class="tq38jsbfw"/></g><g filter="url(#iiKDn7b)"><path fill="url(#ilWACCe)" class="k2apa8lhy"/></g><path class="gt8ejtb0z"/><path fill="url(#il16Ydb)" class="q-ofi9alp"/><path class="mu_s2x4zb"/><g filter="url(#ihSWTJb)"><path fill="url(#i6zAFHd)" class="b8tfghb5e"/></g><g filter="url(#i8LJcQX)"><ellipse transform="rotate(-27.914 11.367 16.642)" class="f4pb0gbgx"/><ellipse fill="url(#iyusx7d)" transform="rotate(-27.914 11.367 16.642)" class="rbxjp8blr"/></g><g filter="url(#i3AGbFb)"><path stroke="url(#izboENd)" class="wn7hqob1y"/></g><g filter="url(#iNKLfMc)"><path stroke="url(#i06Rvdb)" class="tgzvp5bla"/></g><defs><radialGradient id="iIrJHrb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.092)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="ixYPiXc" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.598)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="icY7ZHs" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.623)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ieplpze" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.58 39.24)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iB9vHWd" cx="0" cy="0" r="1" gradientTransform="rotate(97.214 1.96 15.352)scale(15.9482 21.6489)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="o-znbtbpj"/><stop offset="1" class="b4qonmbiw"/></radialGradient><radialGradient id="iz7MKqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.321 15.72)" gradientUnits="userSpaceOnUse"><stop class="nve4o1bcy"/><stop offset="1" class="lekcnobli"/></radialGradient><radialGradient id="ipPymdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 15.658)" gradientUnits="userSpaceOnUse"><stop class="p9gefx6_p"/><stop offset="1" class="lshnc7l2t"/></radialGradient><radialGradient id="iTsphvE" cx="0" cy="0" r="1" gradientTransform="rotate(138.793 10.655 9.132)scale(11.547 9.95893)" gradientUnits="userSpaceOnUse"><stop class="abit7xbbd"/><stop offset="1" class="xcdebr0ob"/></radialGradient><radialGradient id="iby38Uc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.4087 8.25997 -14.04691 -10.89865 22.832 3.708)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iTjT4pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.12461 -3.47136 1.70486 -.0612 8.127 11.648)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iKWNHGe" cx="0" cy="0" r="1" gradientTransform="matrix(1.60216 -3.6672 2.99087 1.30668 23.829 14.853)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="igvIxYb" cx="0" cy="0" r="1" gradientTransform="matrix(1.85139 2.29723 -2.0283 1.63465 14.5 2.052)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iiRl7kb" cx="0" cy="0" r="1" gradientTransform="rotate(76.961 7.33 11.871)scale(1.4992 2.4647)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="i0YK9Mz" cx="0" cy="0" r="1" gradientTransform="matrix(1.35294 1.67337 -3.7494 3.03145 7.842 5.275)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iNehz7U" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.556 21.088)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="icCcsSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.442)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWeyuob" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.95 3.693)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="il16Ydb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.442)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iyusx7d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.15 3.033)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iTdFI9b" width="6.427" height="6.227" x="3.979" y="14.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19887"/></filter><filter id="i9IeLtd" width="4.711" height="4.711" x="4.737" y="15.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".25"/></filter><filter id="ihTQeJb" width="6.477" height="6.477" x="21.72" y="14.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19887"/></filter><filter id="iyOJPEe" width="4.711" height="4.711" x="22.478" y="15.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".25"/></filter><filter id="io7Dckb" width="19.345" height="22.68" x="6.327" y="7.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.607843 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19887"/></filter><filter id="i84zoKa" width="23.5" height="15.5" x="4.196" y="1.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19887"/></filter><filter id="i0kkO8d" width="4.782" height="6.5" x="13.11" y="16.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".375"/></filter><filter id="ic4NKye" width="4" height="5.5" x="13.946" y="16.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".125"/></filter><filter id="iL64rVv" width="5.34" height="3.147" x="18.151" y="11.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19887"/></filter><filter id="ivCyzFv" width="5.341" height="3.147" x="8.551" y="11.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19887"/></filter><filter id="ikdYbxe" width="1.294" height="1.125" x="18.727" y="16.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".05"/></filter><filter id="iiKDn7b" width="1.316" height="1.357" x="20.38" y="16.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".1"/></filter><filter id="ihSWTJb" width="1.493" height="1.594" x="12.097" y="16.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".1"/></filter><filter id="i8LJcQX" width="1.529" height="1.141" x="10.603" y="16.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".05"/></filter><filter id="i3AGbFb" width="4.949" height="2.304" x="18.293" y="11.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".25"/></filter><filter id="iNKLfMc" width="5.094" height="2.41" x="8.56" y="12.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19887" stdDeviation=".25"/></filter><linearGradient id="i15r5sd" x1="7.092" x2="5.898" y1="18.611" y2="18.611" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iz14K9b" x1="26.859" x2="25.332" y1="16.056" y2="20.786" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iePW6JR" x1="25.081" x2="9.231" y1="18.818" y2="20.94" gradientUnits="userSpaceOnUse"><stop class="w_zczw3bj"/><stop offset="1" class="bg384sb2z"/></linearGradient><linearGradient id="ildss2X" x1="6.327" x2="10.196" y1="23.485" y2="23.283" gradientUnits="userSpaceOnUse"><stop class="uiznndb6j"/><stop offset="1" class="o4oies06f"/></linearGradient><linearGradient id="iF14r2c" x1="6.881" x2="12.293" y1="17.594" y2="7.981" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="ijGazjl" x1="14.335" x2="16.084" y1="20.047" y2="20.047" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="i3sQSLc" x1="17.696" x2="15.784" y1="20.649" y2="20.622" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iGgvMuU" x1="16.309" x2="16.309" y1="22.033" y2="20.965" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iKIWK5c" x1="16.181" x2="16.181" y1="22.111" y2="21.799" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="iUOC6UK" x1="14.012" x2="14.824" y1="25.045" y2="23.763" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="ilWACCe" x1="21.46" x2="20.875" y1="16.92" y2="17.281" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6zAFHd" x1="13.26" x2="12.675" y1="16.92" y2="17.281" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izboENd" x1="21.489" x2="20.706" y1="12.93" y2="11.329" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="i06Rvdb" x1="11.597" x2="9.379" y1="12.692" y2="11.762" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-blonde-hair-light" /></template>
<style>
.a59tocc-c {
  cx: 24.833px;
  cy: 18.092px;
  r: 3.113px;
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.abit7xbbd {
  stop-color: var(--svg-color--ffe3c5, #FFE3C5);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.b4qonmbiw {
  stop-color: var(--svg-color--b67a96, #B67A96);
}

.b8tfghb5e {
  d: path("M13.39 17.399c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bg384sb2z {
  stop-color: var(--svg-color--daa495, #DAA495);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.etm-usb1o {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.234 17.56l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.f4pb0gbgx {
  cx: 11.367px;
  cy: 16.642px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fgk5p2gyi {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.433 17.864l-1.53 3.17c-.19.651.266 1.303.91 1.303h1.375c.645 0 1.1-.662.91-1.303l-.929-3.17c-.199-.702-.527-.702-.736 0");
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g8udy2bfd {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m24.933 6.012l.8.398c1.4.696 2.2 2.287 1.9 3.978l-1.1 5.67c-.098.585-.485.979-1.066.993h-.034s.1-1.69.2-2.685c.081-.807-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.393c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.1-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.591l-.3.298c-.4.299-.6.896-.6 1.393c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.991l-1.1-5.67c-.2-1.59.6-3.182 2-3.878l.8-.398c.5-.299 1-.696 1.501-1.094l1.8-1.89c1.1-.995 2.701-1.293 4.102-.597c1 .299 2.1.299 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.492c.4.497.9.795 1.5 1.094");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gt8ejtb0z {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.424c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hhh8z8ibj {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.594a.95.95 0 0 1 .953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.44h-1.686a.86.86 0 0 1-.113-.44");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i8pk5x4lf {
  d: path("m6.436 16.95l.091.002s-.1-1.591-.2-2.685c0-.497.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.393c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.1.8.497.8.994v1.592c0 .596.3 1.193.7 1.591c.937.656.879 1.017.801 1.79c-.1.995-.2 2.686-.2 2.686h.034l-.496 7.381c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.k2apa8lhy {
  d: path("M21.496 17.375a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l95nrybxs {
  cx: 7.092px;
  cy: 18.092px;
  r: 3.113px;
}

.lekcnobli {
  stop-color: var(--svg-color--f6b8a7, #F6B8A7);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lshnc7l2t {
  stop-color: var(--svg-color--cf948d, #CF948D);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mu_s2x4zb {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.595a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .158.037.31.105.438h1.687a.95.95 0 0 0 .114-.439");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.na9lb6b3a {
  d: path("m15.234 17.56l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.nfhmpfbow {
  cx: 7.092px;
  cy: 18.092px;
  r: 1.855px;
}

.nve4o1bcy {
  stop-color: var(--svg-color--f6b8a7, #F6B8A7);
}

.o-znbtbpj {
  stop-color: var(--svg-color--b67a96, #B67A96);
  stop-opacity: 0;
}

.o4oies06f {
  stop-color: var(--svg-color--e8ad95, #E8AD95);
  stop-opacity: 0;
}

.ocwpl4b1u {
  d: path("M20.013 15.93a1.664 1.664 0 0 1 1.604 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p9gefx6_p {
  stop-color: var(--svg-color--cf948d, #CF948D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q-ofi9alp {
  d: path("M11.87 15.93a1.664 1.664 0 0 0-1.604 2.103h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qmv9bbywi {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m8.91 13.02l.002-.001l.004-.003l.008-.007l.022-.018l.067-.05q.083-.062.222-.15c.186-.117.45-.262.783-.393a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r49s0uo1k {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m22.883 13.02l-.002-.002l-.004-.003l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.393a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.536");
}

.rbxjp8blr {
  cx: 11.367px;
  cy: 16.642px;
  rx: 0.726px;
  ry: 0.368px;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.tgzvp5bla {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.717c.61-.54 1.942-1.107 3.593-.844");
}

.tm83ogpeh {
  d: path("m24.933 6.012l.8.398c1.4.696 2.2 2.287 1.9 3.978l-1.1 5.67c-.098.585-.485.979-1.066.993h-.034s.1-1.69.2-2.685c.081-.807-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.393c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.1-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.591l-.3.298c-.4.299-.6.896-.6 1.393c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.991l-1.1-5.67c-.2-1.59.6-3.182 2-3.878l.8-.398c.5-.299 1-.696 1.501-1.094l1.8-1.89c1.1-.995 2.701-1.293 4.102-.597c1 .299 2.1.299 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.492c.4.497.9.795 1.5 1.094");
}

.tq38jsbfw {
  d: path("M19.891 16.282c.119.159-.13.352-.41.563c-.283.21-.492.359-.61.2c-.119-.158.014-.458.295-.668c.282-.211.607-.253.725-.095");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ucqn5mg9d {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.424c1.217 0 2.245.84 2.525 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.uiznndb6j {
  stop-color: var(--svg-color--e8ad95, #E8AD95);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w_zczw3bj {
  stop-color: var(--svg-color--ffdbc0, #FFDBC0);
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wn7hqob1y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.75c.802-.14 2.366-.1 3.449.742");
}

.wq3eyabtb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.282c.119.159-.13.352-.41.563c-.283.21-.492.359-.61.2c-.119-.158.014-.458.295-.668c.282-.211.607-.253.725-.095");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xcdebr0ob {
  stop-color: var(--svg-color--ffe3c5, #FFE3C5);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.yczt3zwsf {
  cx: 24.833px;
  cy: 18.092px;
  r: 1.855px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zh3sjtblp {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.272a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.6a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.397a.34.34 0 0 0-.4-.065a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.221-2.56-.607Z");
}

.zjd0whgav {
  cx: 24.833px;
  cy: 18.092px;
  r: 1.855px;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

</style>
