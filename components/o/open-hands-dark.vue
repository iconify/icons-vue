<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixy6iie)"><path class="v-fay_bca"/></g><path fill="url(#i3VvpDe)" class="xuamiuqtr"/><path fill="url(#idWFAld)" class="xuamiuqtr"/><rect fill="url(#iULCAzb)" transform="rotate(-45 .623 22.25)" class="j63717bqt"/><rect fill="url(#iY3sFUd)" transform="rotate(-45 .623 22.25)" class="j63717bqt"/><path fill="url(#iyQjQge)" class="edqg_jb3v"/><path fill="url(#iu9eFVc)" class="edqg_jb3v"/><rect fill="url(#iL2X0ld)" transform="rotate(-39.184 5.342 15.1)" class="p85nmebgf"/><rect fill="url(#iFsluBb)" transform="rotate(-39.184 5.342 15.1)" class="p85nmebgf"/><rect fill="url(#i87nzUd)" transform="rotate(-39.184 5.342 15.1)" class="p85nmebgf"/><rect fill="url(#iG2NBHd)" transform="rotate(-39.184 5.342 15.1)" class="p85nmebgf"/><path fill="url(#iqEkhXb)" class="aajaq4bhv"/><path fill="url(#ivJiDFc)" class="aajaq4bhv"/><path fill="url(#iajv13d)" class="hpeaddb5p"/><g filter="url(#ib3OiAc)"><path class="tnkb44coi"/></g><g filter="url(#iZ9hN3d)"><path class="citi16bgx"/></g><g filter="url(#ifN5tkQ)"><path class="gv-_k0bhh"/></g><g filter="url(#iUoIbAc)"><path class="z6kshzbjp"/></g><g filter="url(#iw9F7ce)"><path fill="url(#inw7x6b)" class="hokg-kwuc"/><path fill="url(#iHF0DCd)" class="hokg-kwuc"/></g><g filter="url(#ichHLbd)"><path stroke="url(#i345gnc)" class="nfhjbcbwr"/></g><g filter="url(#i5tIurD)"><path class="hlm3-v17u"/></g><path fill="url(#iB0amec)" class="rur03hbiw"/><rect fill="url(#its3vae)" transform="scale(-1 1)rotate(-45 11.17 49.002)" class="awd4szbtd"/><rect fill="url(#ido9oHb)" transform="scale(-1 1)rotate(-45 11.17 49.002)" class="awd4szbtd"/><path fill="url(#i3uR0VS)" class="aj-k0drpd"/><path fill="url(#i88ls6d)" class="aj-k0drpd"/><path fill="url(#iVfWkFc)" class="aj-k0drpd"/><rect fill="url(#iMLAxxe)" transform="scale(-1 1)rotate(-39.184 7.883 45)" class="awd4szbtd"/><rect fill="url(#ifndr2b)" transform="scale(-1 1)rotate(-39.184 7.883 45)" class="awd4szbtd"/><rect fill="url(#i6jdFYP)" transform="scale(-1 1)rotate(-39.184 7.883 45)" class="awd4szbtd"/><rect fill="url(#iBWFsEe)" transform="scale(-1 1)rotate(-39.184 7.883 45)" class="awd4szbtd"/><rect fill="url(#iV6CZ3b)" transform="scale(-1 1)rotate(-39.184 7.883 45)" class="awd4szbtd"/><path fill="url(#ifXbfsd)" class="okq_mbbqs"/><path fill="url(#i9O46Kb)" class="okq_mbbqs"/><path fill="url(#iLn79fd)" class="xcejkcb8t"/><path fill="url(#iPsvKxd)" class="xcejkcb8t"/><g filter="url(#ir0660L)"><path fill="url(#iFdined)" class="iqbdnqsru"/><path fill="url(#iEpTWAc)" class="iqbdnqsru"/></g><g filter="url(#inUu0Dd)"><path stroke="url(#iWzouke)" class="e09lagbxm"/></g><g filter="url(#iaFyjQe)"><ellipse transform="rotate(48.289 25.068 14.994)" class="qe5iz-miv"/></g><g filter="url(#iSbW82d)"><ellipse transform="rotate(48.289 28.006 16)" class="j6pzy52sg"/></g><g filter="url(#ituzQFb)"><ellipse transform="rotate(48.289 29.081 18.86)" class="tjzq9rbwi"/></g><g filter="url(#imNTxEc)"><ellipse transform="rotate(48.289 29.72 22.132)" class="vhx5hobjp"/></g><defs><radialGradient id="idWFAld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.58166 1.53445 -1.24098 -1.27916 15.726 16.045)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="iULCAzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00542 0 0 -3.8359 3.81 24.393)" gradientUnits="userSpaceOnUse"><stop class="kpgkf5_tx"/><stop offset="1" class="l3f_erbwt"/></radialGradient><radialGradient id="iY3sFUd" cx="0" cy="0" r="1" gradientTransform="rotate(89.479 -10.086 12.089)scale(1.62111 2.4029)" gradientUnits="userSpaceOnUse"><stop class="eq9vtjbzr"/><stop offset="1" class="glmm398do"/></radialGradient><radialGradient id="iyQjQge" cx="0" cy="0" r="1" gradientTransform="matrix(-.84222 .84717 -3.4106 -3.39066 5.694 19.044)" gradientUnits="userSpaceOnUse"><stop class="x98zehbja"/><stop offset="1" class="x5ge8rc-b"/></radialGradient><radialGradient id="iu9eFVc" cx="0" cy="0" r="1" gradientTransform="rotate(42.014 -22.075 10.904)scale(2.44817 4.46103)" gradientUnits="userSpaceOnUse"><stop class="xjezrxbyq"/><stop offset="1" class="fojmw3b_o"/></radialGradient><radialGradient id="i87nzUd" cx="0" cy="0" r="1" gradientTransform="rotate(-176.759 4.599 11.008)scale(1.07018 3.84413)" gradientUnits="userSpaceOnUse"><stop class="x-gtvebnh"/><stop offset="1" class="qs5jjeb1a"/></radialGradient><radialGradient id="iqEkhXb" cx="0" cy="0" r="1" gradientTransform="rotate(144.45 .956 9.892)scale(1.20415 4.7597)" gradientUnits="userSpaceOnUse"><stop class="u649-8b-n"/><stop offset="1" class="eefpdvbuw"/></radialGradient><radialGradient id="ivJiDFc" cx="0" cy="0" r="1" gradientTransform="rotate(87.51 -5.22 9.66)scale(1.45222 3.17662)" gradientUnits="userSpaceOnUse"><stop class="w_qy1ub0c"/><stop offset="1" class="f1sbjob3z"/></radialGradient><radialGradient id="iajv13d" cx="0" cy="0" r="1" gradientTransform="matrix(1.01062 .13927 -.4062 2.9477 12.844 16.595)" gradientUnits="userSpaceOnUse"><stop class="cejoejbaw"/><stop offset="1" class="d-9xlccvo"/></radialGradient><radialGradient id="inw7x6b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03123 2.5769 -2.26094 -5.29174 15.938 21.762)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="m11hpabfh"/><stop offset=".966" class="u_lab0irz"/></radialGradient><radialGradient id="iHF0DCd" cx="0" cy="0" r="1" gradientTransform="rotate(-135.346 13.102 11.175)scale(9.65766 9.46757)" gradientUnits="userSpaceOnUse"><stop offset=".829" class="ehperlbpp"/><stop offset="1" class="kl0j6ebyi"/></radialGradient><radialGradient id="its3vae" cx="0" cy="0" r="1" gradientTransform="matrix(-.91703 .05524 -.17617 -2.92472 3.007 2.852)" gradientUnits="userSpaceOnUse"><stop class="z8_vanbxh"/><stop offset="1" class="um7en9bzl"/></radialGradient><radialGradient id="ido9oHb" cx="0" cy="0" r="1" gradientTransform="matrix(.30933 2.96102 -2.68543 .28054 1.316 -.915)" gradientUnits="userSpaceOnUse"><stop class="n9vcambar"/><stop offset="1" class="e_kfwziyy"/></radialGradient><radialGradient id="i3uR0VS" cx="0" cy="0" r="1" gradientTransform="matrix(.99749 .90947 -2.87886 3.15745 26.152 18.981)" gradientUnits="userSpaceOnUse"><stop class="e26ljmbtl"/><stop offset="1" class="r39dakbls"/></radialGradient><radialGradient id="i88ls6d" cx="0" cy="0" r="1" gradientTransform="rotate(142.024 12.087 13.867)scale(2.84402 7.08403)" gradientUnits="userSpaceOnUse"><stop class="h1c5vrc4n"/><stop offset="1" class="hpy24sbsy"/></radialGradient><radialGradient id="iVfWkFc" cx="0" cy="0" r="1" gradientTransform="rotate(-130.786 18.793 4.9)scale(1.05246 2.26293)" gradientUnits="userSpaceOnUse"><stop class="eixcx7btr"/><stop offset="1" class="rv-9ycb0w"/></radialGradient><radialGradient id="ifndr2b" cx="0" cy="0" r="1" gradientTransform="rotate(-176.842 1.704 3.579)scale(.63757 2.23301)" gradientUnits="userSpaceOnUse"><stop class="k63icwbow"/><stop offset="1" class="o1bxa4_9x"/></radialGradient><radialGradient id="iV6CZ3b" cx="0" cy="0" r="1" gradientTransform="matrix(.21581 2.55454 -2.31679 .19573 1.263 -.186)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="ifXbfsd" cx="0" cy="0" r="1" gradientTransform="matrix(.99155 .76912 -3.04015 3.91936 24.504 17.484)" gradientUnits="userSpaceOnUse"><stop class="igz1n6bmx"/><stop offset="1" class="biqs7fbhg"/></radialGradient><radialGradient id="i9O46Kb" cx="0" cy="0" r="1" gradientTransform="rotate(133.132 11.271 13.672)scale(2.03401 2.19149)" gradientUnits="userSpaceOnUse"><stop class="j9tcr3bwv"/><stop offset="1" class="bn4a00bvh"/></radialGradient><radialGradient id="iLn79fd" cx="0" cy="0" r="1" gradientTransform="matrix(1.56208 .625 -2.78094 6.95045 16 15.86)" gradientUnits="userSpaceOnUse"><stop class="r30u246fw"/><stop offset="1" class="q0oxgnf-n"/></radialGradient><radialGradient id="iPsvKxd" cx="0" cy="0" r="1" gradientTransform="rotate(115.829 4.98 13.974)scale(4.89529 3.33547)" gradientUnits="userSpaceOnUse"><stop class="cy6ehgw4w"/><stop offset="1" class="cbd3evn5v"/></radialGradient><radialGradient id="iFdined" cx="0" cy="0" r="1" gradientTransform="matrix(3.91145 2.47904 -2.17508 3.43186 18 22.392)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="i1x_wqbtu"/><stop offset=".844" class="u9ikxob2z"/></radialGradient><radialGradient id="iEpTWAc" cx="0" cy="0" r="1" gradientTransform="rotate(-44.654 43.212 -7.057)scale(9.65766 9.46757)" gradientUnits="userSpaceOnUse"><stop offset=".829" class="g52awts0e"/><stop offset="1" class="jupbeww_g"/></radialGradient><filter id="ixy6iie" width="15.006" height="16.453" x="1.245" y="13.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.133333 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.172549 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3664" result="effect2_innerShadow_20020_3664"/></filter><filter id="ib3OiAc" width="5.111" height="5.631" x="1.918" y="20.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".375"/></filter><filter id="iZ9hN3d" width="5.111" height="5.631" x="2.402" y="17.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".375"/></filter><filter id="ifN5tkQ" width="6.581" height="7.282" x="3.429" y="14.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".375"/></filter><filter id="iUoIbAc" width="7.294" height="7.977" x="6.255" y="13.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".5"/></filter><filter id="iw9F7ce" width="11.402" height="11.423" x="5.191" y="18.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".5"/></filter><filter id="ichHLbd" width="3.108" height="9.031" x="13.407" y="15.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".5"/></filter><filter id="i5tIurD" width="15.006" height="16.453" x="16" y="13.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0705882 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3664" result="effect2_innerShadow_20020_3664"/></filter><filter id="ir0660L" width="11.402" height="11.423" x="15.407" y="18.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".5"/></filter><filter id="inUu0Dd" width="2.838" height="5.422" x="17.162" y="15.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".25"/></filter><filter id="iaFyjQe" width="3.333" height="3.361" x="23.401" y="13.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".5"/></filter><filter id="iSbW82d" width="3.333" height="3.361" x="26.339" y="14.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".5"/></filter><filter id="ituzQFb" width="3.333" height="3.361" x="27.415" y="17.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".5"/></filter><filter id="imNTxEc" width="3.333" height="3.361" x="28.053" y="20.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3664" stdDeviation=".5"/></filter><linearGradient id="i3VvpDe" x1="17.024" x2="14.003" y1="21.333" y2="21.333" gradientUnits="userSpaceOnUse"><stop class="lh1z8q3bk"/><stop offset="1" class="mmj7kgc7f"/></linearGradient><linearGradient id="iL2X0ld" x1="8.743" x2="7.123" y1="18.238" y2="18.202" gradientUnits="userSpaceOnUse"><stop class="vs7zzbbji"/><stop offset="1" class="edrtumbhu"/></linearGradient><linearGradient id="iFsluBb" x1="4.915" x2="6.738" y1="19.197" y2="19.276" gradientUnits="userSpaceOnUse"><stop class="sgmt3fb2a"/><stop offset="1" class="c40z1474u"/></linearGradient><linearGradient id="iG2NBHd" x1="6.717" x2="6.828" y1="23.74" y2="19.834" gradientUnits="userSpaceOnUse"><stop offset=".438" class="vdkaxlwfb"/><stop offset="1" class="bciuqbxbv"/></linearGradient><linearGradient id="i345gnc" x1="14.961" x2="14.961" y1="14.579" y2="23.142" gradientUnits="userSpaceOnUse"><stop class="mip3wjw9k"/><stop offset="1" class="evixpqbbz"/></linearGradient><linearGradient id="iB0amec" x1="14.976" x2="17.998" y1="21.333" y2="21.333" gradientUnits="userSpaceOnUse"><stop class="t5cclfbwg"/><stop offset="1" class="c2nfiw14f"/></linearGradient><linearGradient id="iMLAxxe" x1="3.487" x2="1.377" y1="2.897" y2="3.112" gradientUnits="userSpaceOnUse"><stop class="efp6bbbsc"/><stop offset="1" class="lid38w2tj"/></linearGradient><linearGradient id="i6jdFYP" x1="-.382" x2="1.071" y1="4.38" y2="4.328" gradientUnits="userSpaceOnUse"><stop class="z-424rb0w"/><stop offset="1" class="gp3yrybct"/></linearGradient><linearGradient id="iBWFsEe" x1="1.442" x2="1.368" y1="6.148" y2="7.822" gradientUnits="userSpaceOnUse"><stop class="bprbj0bhg"/><stop offset="1" class="ellvfihez"/></linearGradient><linearGradient id="iWzouke" x1="18.033" x2="18.033" y1="13.662" y2="22.225" gradientUnits="userSpaceOnUse"><stop class="msa8jyb7x"/><stop offset="1" class="iv9_edb6r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:open-hands-dark" /></template>
<style>
.aajaq4bhv {
  d: path("M5.97 15.547c.04.254.146.502.32.716l3.756 4.608l.014.016a1.5 1.5 0 0 1-1.885.89l-3.76-3.76a1.5 1.5 0 0 0-.58-.36l-.444-.444a1.5 1.5 0 1 1 2.123-2.123z");
}

.aj-k0drpd {
  d: path("M29.709 18.017a1.5 1.5 0 0 1 0 2.123l-.62.62a1.5 1.5 0 0 0-.895.43l-3.584 3.583a1.501 1.501 0 0 1-1.227-2.553l4.203-4.203a1.5 1.5 0 0 1 2.123 0");
}

.awd4szbtd {
  width: 3.002px;
  height: 8.946px;
  rx: 1.501px;
}

.bciuqbxbv {
  stop-color: var(--svg-color--4d3338, #4D3338);
  stop-opacity: 0;
}

.biqs7fbhg {
  stop-color: var(--svg-color--240f0d, #240F0D);
  stop-opacity: 0;
}

.bn4a00bvh {
  stop-color: var(--svg-color--5e4844, #5E4844);
  stop-opacity: 0;
}

.bprbj0bhg {
  stop-color: var(--svg-color--4c3237, #4C3237);
  stop-opacity: 0;
}

.c2nfiw14f {
  stop-color: var(--svg-color--2e1718, #2E1718);
  stop-opacity: 0;
}

.c40z1474u {
  stop-color: var(--svg-color--2a1315, #2A1315);
  stop-opacity: 0;
}

.cbd3evn5v {
  stop-color: var(--svg-color--5f4945, #5F4945);
  stop-opacity: 0;
}

.cejoejbaw {
  stop-color: var(--svg-color--2e1e1d, #2E1E1D);
}

.citi16bgx {
  fill: var(--svg-color--614e4d, #614E4D);
  d: path("M3.282 18.809a.441.441 0 1 1 .626-.622l2.855 2.893l-.103 1.107z");
}

.cy6ehgw4w {
  stop-color: var(--svg-color--5f4945, #5F4945);
}

.d-9xlccvo {
  stop-color: var(--svg-color--2e1e1d, #2E1E1D);
  stop-opacity: 0;
}

.e_kfwziyy {
  stop-color: var(--svg-color--5f4744, #5F4744);
  stop-opacity: 0;
}

.e09lagbxm {
  stroke-linecap: round;
  d: path("M18.172 16.704c-.078 1.688.313 2.657.828 3.422");
}

.e26ljmbtl {
  stop-color: var(--svg-color--2d1614, #2D1614);
}

.edqg_jb3v {
  d: path("M2.292 18.017a1.5 1.5 0 0 0 0 2.123l.62.62c.327.035.644.179.895.43l3.584 3.583a1.5 1.5 0 0 0 1.227-2.553l-4.203-4.203a1.5 1.5 0 0 0-2.123 0");
}

.edrtumbhu {
  stop-color: var(--svg-color--634f4c, #634F4C);
  stop-opacity: 0;
}

.eefpdvbuw {
  stop-color: var(--svg-color--220e0d, #220E0D);
  stop-opacity: 0;
}

.efp6bbbsc {
  stop-color: var(--svg-color--40312f, #40312F);
}

.ehperlbpp {
  stop-color: var(--svg-color--432b2b, #432B2B);
  stop-opacity: 0;
}

.eixcx7btr {
  stop-color: var(--svg-color--321a1b, #321A1B);
}

.ellvfihez {
  stop-color: var(--svg-color--4c3237, #4C3237);
}

.eq9vtjbzr {
  stop-color: var(--svg-color--4b3c39, #4B3C39);
}

.evixpqbbz {
  stop-color: var(--svg-color--64504f, #64504F);
  stop-opacity: 0;
}

.f1sbjob3z {
  stop-color: var(--svg-color--574441, #574441);
  stop-opacity: 0;
}

.fojmw3b_o {
  stop-color: var(--svg-color--4a3a36, #4A3A36);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g52awts0e {
  stop-color: var(--svg-color--5a4847, #5A4847);
  stop-opacity: 0;
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.glmm398do {
  stop-color: var(--svg-color--4b3c39, #4B3C39);
  stop-opacity: 0;
}

.gp3yrybct {
  stop-color: var(--svg-color--3e2426, #3E2426);
  stop-opacity: 0;
}

.gv-_k0bhh {
  fill: var(--svg-color--5d4a49, #5D4A49);
  d: path("M4.286 15.974a.44.44 0 1 1 .666-.576l4.308 5.005l-.587.624z");
}

.h1c5vrc4n {
  stop-color: var(--svg-color--5b4440, #5B4440);
}

.hlm3-v17u {
  fill: var(--svg-color--4c3237, #4C3237);
  d: path("M25.496 14.151a1.5 1.5 0 0 1 .534 1.396l.457-.457a1.501 1.501 0 0 1 2.123 2.123l-.444.443a1.501 1.501 0 0 1 1.543 2.484l-.62.62a1.5 1.5 0 0 1 1.227 2.553l-4.203 4.203a1.5 1.5 0 0 1-.27.214l-.366.342c-1 .93-2.533 1.945-4.445 1.945v-.001h-.105c-2.636 0-4.79-2.103-4.92-4.75H16V18.69h.002c-.006-.539.014-1.133.076-1.742a1.565 1.565 0 0 1 3.128.033h.006l.005.127v.002c.008.165.022.461.022.834c0 .345.012.723.092 1.105c.021.104.158.114.245-.006q.024-.035.052-.068l3.756-4.608a1.5 1.5 0 0 1 2.111-.215");
}

.hokg-kwuc {
  d: path("M15.2 22.658c-1.74-.573-2.34-2.05-2.35-2.98c-.961-.152-3.373-.05-5.028 1.62c-1.7 1.716-1.676 3.793-1.608 4.755c.733.705 2.05 1.83 2.996 2.445c1.181.77 3.16.825 4.534-.412c1.212-1.091 1.988-2.516 1.829-4.975a.525.525 0 0 0-.372-.453");
}

.hpeaddb5p {
  d: path("M12.794 16.98a1.565 1.565 0 0 1 3.128-.034a17 17 0 0 1-.086 3.954l-3.562-.86c.445-.695.488-1.451.488-2.097c0-.373.014-.669.022-.834l.005-.13z");
}

.hpy24sbsy {
  stop-color: var(--svg-color--5b4440, #5B4440);
  stop-opacity: 0;
}

.i1x_wqbtu {
  stop-color: var(--svg-color--4d3537, #4D3537);
}

.igz1n6bmx {
  stop-color: var(--svg-color--240f0d, #240F0D);
}

.iqbdnqsru {
  d: path("M16.8 22.658c1.741-.573 2.342-2.05 2.35-2.98c.962-.152 3.374-.05 5.029 1.62c1.7 1.716 1.676 3.793 1.608 4.755c-.733.705-2.05 1.83-2.996 2.445c-1.181.77-3.16.825-4.534-.412c-1.212-1.091-1.989-2.516-1.829-4.975a.525.525 0 0 1 .372-.453");
}

.iv6sy1bym {
  stop-color: var(--svg-color--65514f, #65514F);
  stop-opacity: 0;
}

.iv9_edb6r {
  stop-color: var(--svg-color--634f4d, #634F4D);
  stop-opacity: 0;
}

.j63717bqt {
  width: 3.002px;
  height: 8.946px;
  x: 0.623px;
  y: 22.251px;
  rx: 1.501px;
}

.j6pzy52sg {
  cx: 28.006px;
  cy: 16px;
  fill: var(--svg-color--66524f, #66524F);
  rx: 0.732px;
  ry: 0.609px;
}

.j9tcr3bwv {
  stop-color: var(--svg-color--5e4844, #5E4844);
}

.jupbeww_g {
  stop-color: var(--svg-color--5a4847, #5A4847);
}

.k63icwbow {
  stop-color: var(--svg-color--311c1b, #311C1B);
}

.kl0j6ebyi {
  stop-color: var(--svg-color--432b2b, #432B2B);
}

.kpgkf5_tx {
  stop-color: var(--svg-color--2c1815, #2C1815);
}

.l3f_erbwt {
  stop-color: var(--svg-color--2c1815, #2C1815);
  stop-opacity: 0;
}

.lh1z8q3bk {
  stop-color: var(--svg-color--412827, #412827);
}

.lid38w2tj {
  stop-color: var(--svg-color--40312f, #40312F);
  stop-opacity: 0;
}

.m11hpabfh {
  stop-color: var(--svg-color--685151, #685151);
}

.mip3wjw9k {
  stop-color: var(--svg-color--64504f, #64504F);
}

.mmj7kgc7f {
  stop-color: var(--svg-color--412827, #412827);
  stop-opacity: 0;
}

.msa8jyb7x {
  stop-color: var(--svg-color--6c5754, #6C5754);
}

.n9vcambar {
  stop-color: var(--svg-color--5f4744, #5F4744);
}

.nfhjbcbwr {
  stroke-linecap: round;
  d: path("M14.907 17.11c.187 1.86.093 3.11 0 6.032");
}

.o1bxa4_9x {
  stop-color: var(--svg-color--311c1b, #311C1B);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.okq_mbbqs {
  d: path("M26.03 15.547c-.04.254-.145.502-.32.716l-3.755 4.608l-.014.016a1.5 1.5 0 0 0 1.885.89l3.76-3.76c.17-.169.368-.29.58-.36l.444-.444a1.501 1.501 0 0 0-2.123-2.123z");
}

.p85nmebgf {
  width: 3.002px;
  height: 8.946px;
  x: 5.342px;
  y: 15.1px;
  rx: 1.501px;
}

.q0oxgnf-n {
  stop-color: var(--svg-color--352b2b, #352B2B);
  stop-opacity: 0;
}

.qe5iz-miv {
  cx: 25.068px;
  cy: 14.994px;
  fill: var(--svg-color--665250, #665250);
  rx: 0.732px;
  ry: 0.609px;
}

.qs5jjeb1a {
  stop-color: var(--svg-color--422a27, #422A27);
  stop-opacity: 0;
}

.r30u246fw {
  stop-color: var(--svg-color--352b2b, #352B2B);
}

.r39dakbls {
  stop-color: var(--svg-color--2d1614, #2D1614);
  stop-opacity: 0;
}

.rur03hbiw {
  d: path("M25.496 14.151a1.5 1.5 0 0 1 .534 1.396l.457-.457a1.501 1.501 0 0 1 2.123 2.123l-.444.443a1.501 1.501 0 0 1 1.543 2.484l-.62.62a1.5 1.5 0 0 1 1.227 2.553l-4.203 4.203a1.5 1.5 0 0 1-.27.214l-.366.342c-1 .93-2.533 1.945-4.445 1.945v-.001h-.105c-2.636 0-4.79-2.103-4.92-4.75H16V18.69h.002c-.006-.539.014-1.133.076-1.742a1.565 1.565 0 0 1 3.128.033h.006l.005.127v.002c.008.165.022.461.022.834c0 .345.012.723.092 1.105c.021.104.158.114.245-.006q.024-.035.052-.068l3.756-4.608a1.5 1.5 0 0 1 2.111-.215");
}

.rv-9ycb0w {
  stop-color: var(--svg-color--321a1b, #321A1B);
  stop-opacity: 0;
}

.sgmt3fb2a {
  stop-color: var(--svg-color--2a1315, #2A1315);
}

.t5cclfbwg {
  stop-color: var(--svg-color--2e1718, #2E1718);
}

.tjzq9rbwi {
  cx: 29.081px;
  cy: 18.86px;
  fill: var(--svg-color--665250, #665250);
  rx: 0.732px;
  ry: 0.609px;
}

.tnkb44coi {
  fill: var(--svg-color--634f4d, #634F4D);
  d: path("M2.797 21.902a.441.441 0 1 1 .626-.622l2.856 2.893l-.104 1.106z");
}

.u_lab0irz {
  stop-color: var(--svg-color--685151, #685151);
  stop-opacity: 0;
}

.u649-8b-n {
  stop-color: var(--svg-color--220e0d, #220E0D);
}

.u9ikxob2z {
  stop-color: var(--svg-color--4d3537, #4D3537);
  stop-opacity: 0;
}

.um7en9bzl {
  stop-color: var(--svg-color--2e1615, #2E1615);
  stop-opacity: 0;
}

.v-fay_bca {
  fill: var(--svg-color--4d3338, #4D3338);
  d: path("M6.505 14.151a1.5 1.5 0 0 0-.534 1.396l-.457-.457a1.501 1.501 0 0 0-2.123 2.123l.444.443a1.501 1.501 0 0 0-1.543 2.484l.62.62a1.501 1.501 0 0 0-1.227 2.553C3.3 24.926 4.86 26.52 6.523 28.071c1 .93 2.533 1.945 4.445 1.945v-.001h.104c2.637 0 4.79-2.103 4.921-4.75H16V18.69a16 16 0 0 0-.078-1.742a1.563 1.563 0 0 0-1.563-1.516c-.859 0-1.556.692-1.565 1.548h-.005l-.005.128v.002c-.008.165-.022.461-.022.834c0 .345-.012.723-.092 1.105c-.021.104-.158.114-.245-.006l-.052-.068l-3.756-4.608a1.5 1.5 0 0 0-2.112-.215");
}

.vdkaxlwfb {
  stop-color: var(--svg-color--4d3338, #4D3338);
}

.vhx5hobjp {
  cx: 29.72px;
  cy: 22.132px;
  fill: var(--svg-color--665250, #665250);
  rx: 0.732px;
  ry: 0.609px;
}

.vs7zzbbji {
  stop-color: var(--svg-color--634f4c, #634F4C);
}

.w_qy1ub0c {
  stop-color: var(--svg-color--574441, #574441);
}

.x-gtvebnh {
  stop-color: var(--svg-color--422a27, #422A27);
}

.x5ge8rc-b {
  stop-color: var(--svg-color--39211f, #39211F);
  stop-opacity: 0;
}

.x98zehbja {
  stop-color: var(--svg-color--39211f, #39211F);
}

.xcejkcb8t {
  d: path("M19.207 16.98a1.565 1.565 0 0 0-3.129-.034a17 17 0 0 0 .087 3.954l3.562-.86c-.445-.695-.488-1.451-.488-2.097c0-.373-.014-.669-.022-.834l-.005-.13z");
}

.xjezrxbyq {
  stop-color: var(--svg-color--4a3a36, #4A3A36);
}

.xm34y9b_d {
  stop-color: var(--svg-color--65514f, #65514F);
}

.xuamiuqtr {
  d: path("M6.505 14.151a1.5 1.5 0 0 0-.534 1.396l-.457-.457a1.501 1.501 0 0 0-2.123 2.123l.444.443a1.501 1.501 0 0 0-1.543 2.484l.62.62a1.501 1.501 0 0 0-1.227 2.553l4.203 4.203q.125.125.27.214l.366.342c1 .93 2.533 1.945 4.445 1.945v-.001h.104c2.637 0 4.79-2.103 4.921-4.75H16V18.69a16 16 0 0 0-.078-1.742a1.563 1.563 0 0 0-1.563-1.516c-.859 0-1.556.692-1.565 1.548h-.005l-.005.128v.002c-.008.165-.022.461-.022.834c0 .345-.012.723-.092 1.105c-.021.104-.158.114-.245-.006l-.052-.068l-3.756-4.608a1.5 1.5 0 0 0-2.112-.215");
}

.z-424rb0w {
  stop-color: var(--svg-color--3e2426, #3E2426);
}

.z6kshzbjp {
  fill: var(--svg-color--5f4c4b, #5F4C4B);
  d: path("M7.364 15.117a.44.44 0 1 1 .662-.578l4.523 5.234l-.564.591z");
}

.z8_vanbxh {
  stop-color: var(--svg-color--2e1615, #2E1615);
}

</style>
