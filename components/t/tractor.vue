<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y537h1yla"/><g filter="url(#iNTrfgc)"><path fill="url(#izopOGd)" class="zxyrmxqdu"/><path fill="url(#izANLEc)" class="zxyrmxqdu"/><path fill="url(#i45bq9y)" class="zxyrmxqdu"/><path fill="url(#igIF1qd)" class="zxyrmxqdu"/><path fill="url(#iHuNDce)" class="zxyrmxqdu"/></g><path fill="url(#i7sH26b)" clip-rule="evenodd" class="o7n_asmpu"/><g filter="url(#iKjh6Hb)"><path clip-rule="evenodd" class="k7r_24z4t"/></g><g filter="url(#iqBK7Vd)"><path fill="url(#ibez9Sc)" class="faa6ge4ul"/><path fill="url(#izBD10c)" class="faa6ge4ul"/><path fill="url(#ixbHygR)" class="faa6ge4ul"/></g><g filter="url(#iyTNumm)"><path class="oqm4lik8g"/></g><g filter="url(#ikbYtid)"><path class="eh_pno2_g"/></g><g filter="url(#iYQYm1I)"><path clip-rule="evenodd" class="kqor_bcjx"/></g><path fill="url(#iHPURmb)" clip-rule="evenodd" class="t4y6q3bin"/><g filter="url(#ixfsd3c)"><path clip-rule="evenodd" class="s9kbc9bnf"/></g><path fill="url(#iG8AG4d)" clip-rule="evenodd" class="vx0yhfpqp"/><g filter="url(#iPJpzdb)"><path fill="url(#i1Pvvjd)" class="okv3qxu0i"/><path fill="url(#iHvdqWg)" class="okv3qxu0i"/></g><path fill="url(#iWUpcdc)" class="rm_jcskye"/><path fill="url(#if8kzSb)" class="rm_jcskye"/><path fill="url(#iIY9tGb)" class="rm_jcskye"/><path class="cxnqgq3fm"/><path fill="url(#i5HVo7b)" class="c1qadxnxc"/><path fill="url(#iFoD39c)" class="c1qadxnxc"/><path fill="url(#ijwBGpb)" class="uclgdjp3h"/><path fill="url(#iGgEtlP)" class="uclgdjp3h"/><path fill="url(#iOwgqhb)" class="k4q-5y-mn"/><path fill="url(#icvwUCe)" class="k4q-5y-mn"/><path fill="url(#iRoOL4c)" class="so0x8kiif"/><path fill="url(#ikrtq6a)" class="so0x8kiif"/><path fill="url(#idENW6b)" class="so0x8kiif"/><path fill="url(#iS3Adod)" class="so0x8kiif"/><g filter="url(#igefghb)"><path class="qkg33yihb"/></g><g filter="url(#iKqrilb)"><circle stroke="url(#i9z2Zoc)" class="cx7ouchrx"/></g><g filter="url(#iq1OSrd)"><circle stroke="url(#iJSRy0b)" class="f_rjqdbqn"/></g><rect fill="url(#igaKfIb)" class="m-a0bxj8c"/><rect fill="url(#ikFRKAC)" class="m-a0bxj8c"/><rect fill="url(#i5lxnBs)" class="m-a0bxj8c"/><rect fill="url(#iDtP8Fb)" class="m-a0bxj8c"/><path fill="url(#idiHbJe)" clip-rule="evenodd" class="ztzradc6u"/><g filter="url(#in2tBBc)"><path stroke="url(#ioQuqVM)" class="yhl16qbsu"/></g><g filter="url(#iXyTMYb)"><path stroke="url(#ihoEeMU)" class="xf8qojm2x"/></g><defs><linearGradient id="izopOGd" x1="24.875" x2="2.625" y1="17.004" y2="17.004" gradientUnits="userSpaceOnUse"><stop class="qah_rl9sc"/><stop offset="1" class="n9st83e1z"/></linearGradient><linearGradient id="izANLEc" x1="15.828" x2="15.828" y1="26.618" y2="23.923" gradientUnits="userSpaceOnUse"><stop class="kza2e647r"/><stop offset="1" class="d7hv1zi4q"/></linearGradient><linearGradient id="igIF1qd" x1="15" x2="15" y1="26" y2="25.594" gradientUnits="userSpaceOnUse"><stop class="p61s8ybxi"/><stop offset="1" class="e2ix3g86r"/></linearGradient><linearGradient id="iHuNDce" x1="15" x2="15" y1="15" y2="17.475" gradientUnits="userSpaceOnUse"><stop offset=".161" class="qxuw3ub5w"/><stop offset="1" class="s2blezbfa"/></linearGradient><linearGradient id="i7sH26b" x1="9.688" x2="9.688" y1="19" y2="17.429" gradientUnits="userSpaceOnUse"><stop class="uayemc_cg"/><stop offset="1" class="omw1x4odf"/></linearGradient><linearGradient id="ibez9Sc" x1="21.964" x2="30.225" y1="22.127" y2="22.127" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iHPURmb" x1="12.375" x2="12.375" y1="25.375" y2="24.531" gradientUnits="userSpaceOnUse"><stop class="o8fzkooti"/><stop offset="1" class="c4lesxtds"/></linearGradient><linearGradient id="iG8AG4d" x1="28.907" x2="28.907" y1="24.047" y2="22.782" gradientUnits="userSpaceOnUse"><stop class="o8fzkooti"/><stop offset="1" class="c4lesxtds"/></linearGradient><linearGradient id="i1Pvvjd" x1="5.906" x2="11.163" y1="24.63" y2="24.63" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iWUpcdc" x1="19.269" x2="19.269" y1="5.721" y2="12.691" gradientUnits="userSpaceOnUse"><stop class="uk3vqeb8o"/><stop offset="1" class="u_1m-kb6b"/></linearGradient><linearGradient id="if8kzSb" x1="25.909" x2="23.84" y1="12.466" y2="12.466" gradientUnits="userSpaceOnUse"><stop class="x_9c5iorj"/><stop offset="1" class="cil3bopgu"/></linearGradient><linearGradient id="iIY9tGb" x1="18" x2="18" y1="7.242" y2="11.234" gradientUnits="userSpaceOnUse"><stop class="y327yp_8h"/><stop offset="1" class="uu_jpzz9d"/></linearGradient><linearGradient id="i5HVo7b" x1="3.265" x2="4.112" y1="20.5" y2="20.488" gradientUnits="userSpaceOnUse"><stop class="p20gbzbyi"/><stop offset="1" class="whoc-y-6u"/></linearGradient><linearGradient id="ijwBGpb" x1="3.265" x2="4.112" y1="18.5" y2="18.488" gradientUnits="userSpaceOnUse"><stop class="p20gbzbyi"/><stop offset="1" class="whoc-y-6u"/></linearGradient><linearGradient id="iOwgqhb" x1="3.265" x2="4.112" y1="22.5" y2="22.488" gradientUnits="userSpaceOnUse"><stop class="p20gbzbyi"/><stop offset="1" class="whoc-y-6u"/></linearGradient><linearGradient id="iRoOL4c" x1="18.124" x2="18.124" y1="6.405" y2="7.834" gradientUnits="userSpaceOnUse"><stop class="nb0nml1qd"/><stop offset="1" class="me_bxj91e"/><stop offset="1" class="pq8bn39zf"/></linearGradient><linearGradient id="ikrtq6a" x1="21.063" x2="21.063" y1="8.469" y2="7.5" gradientUnits="userSpaceOnUse"><stop class="acpf3dhmz"/><stop offset="1" class="ufft4gttv"/></linearGradient><linearGradient id="iS3Adod" x1="20" x2="20" y1="6" y2="6.078" gradientUnits="userSpaceOnUse"><stop class="t--w5zb2b"/><stop offset="1" class="kkrvdacwk"/></linearGradient><linearGradient id="i9z2Zoc" x1="9.489" x2="5.883" y1="22.844" y2="27.1" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iJSRy0b" x1="27.66" x2="22.098" y1="19.469" y2="26.034" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="igaKfIb" x1="9.047" x2="9.75" y1="14.969" y2="14.969" gradientUnits="userSpaceOnUse"><stop class="jk4iasb6y"/><stop offset="1" class="is-42911n"/></linearGradient><linearGradient id="i5lxnBs" x1="9.656" x2="9.656" y1="17.109" y2="16.422" gradientUnits="userSpaceOnUse"><stop class="v9lqhkqys"/><stop offset="1" class="vx3snlb0l"/></linearGradient><linearGradient id="iDtP8Fb" x1="9.047" x2="9.281" y1="14.375" y2="14.375" gradientUnits="userSpaceOnUse"><stop class="hv1kl4b9t"/><stop offset="1" class="jrlerbcbk"/></linearGradient><linearGradient id="idiHbJe" x1="10.094" x2="9.047" y1="13.888" y2="13.888" gradientUnits="userSpaceOnUse"><stop class="mudrlubcd"/><stop offset="1" class="ylyfhvhfa"/></linearGradient><linearGradient id="ioQuqVM" x1="6.795" x2="13.347" y1="20.146" y2="21.916" gradientUnits="userSpaceOnUse"><stop class="l0-x2wbul"/><stop offset="1" class="dksbgmbuv"/></linearGradient><linearGradient id="ihoEeMU" x1="18.772" x2="30.3" y1="16.015" y2="19.337" gradientUnits="userSpaceOnUse"><stop class="l0-x2wbul"/><stop offset="1" class="dksbgmbuv"/></linearGradient><filter id="iNTrfgc" width="27" height="11" x="2" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.521569 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10906"/></filter><filter id="iKjh6Hb" width="8.788" height="6.5" x="4.5" y="19.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10906" stdDeviation=".375"/></filter><filter id="iqBK7Vd" width="11" height="11.15" x="19" y="18.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10906"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10906" result="effect2_innerShadow_18_10906"/></filter><filter id="iyTNumm" width="4.131" height="4.131" x="22.434" y="21.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10906"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10906" result="effect2_innerShadow_18_10906"/></filter><filter id="ikbYtid" width="12.781" height="9.051" x="15.625" y="15.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10906" stdDeviation=".375"/></filter><filter id="iYQYm1I" width="7.49" height="5.25" x="5.52" y="19.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.239216 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10906"/></filter><filter id="ixfsd3c" width="13.01" height="7.75" x="17" y="15.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.239216 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10906"/></filter><filter id="iPJpzdb" width="7" height="7.15" x="4.02" y="22.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10906"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10906" result="effect2_innerShadow_18_10906"/></filter><filter id="igefghb" width="2.647" height="2.647" x="6.197" y="24.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10906"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10906" result="effect2_innerShadow_18_10906"/></filter><filter id="iKqrilb" width="7.031" height="7.031" x="4.188" y="21.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10906" stdDeviation=".375"/></filter><filter id="iq1OSrd" width="9.875" height="9.875" x="19.969" y="18.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10906" stdDeviation=".375"/></filter><filter id="in2tBBc" width="7.242" height="4.499" x="5.687" y="20.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10906" stdDeviation=".125"/></filter><filter id="iXyTMYb" width="12.781" height="6.939" x="17.094" y="16.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10906" stdDeviation=".125"/></filter><radialGradient id="i45bq9y" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48224 4.40183 -2.63683 -.8879 20.903 23.608)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="kza2e647r"/><stop offset="1" class="d7hv1zi4q"/></radialGradient><radialGradient id="izBD10c" cx="0" cy="0" r="1" gradientTransform="matrix(1.24273 -2.73154 2.853 1.29799 24.5 23.018)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="ixbHygR" cx="0" cy="0" r="1" gradientTransform="matrix(1.01563 .67188 -.75497 1.14124 26 23.89)" gradientUnits="userSpaceOnUse"><stop class="f6-f-cyvv"/><stop offset="1" class="qdmn3ybao"/></radialGradient><radialGradient id="iHvdqWg" cx="0" cy="0" r="1" gradientTransform="matrix(.79083 -1.73826 1.81555 .826 7.52 25.197)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iFoD39c" cx="0" cy="0" r="1" gradientTransform="matrix(-.35586 -.16435 .16005 -.34654 4 20.736)" gradientUnits="userSpaceOnUse"><stop class="vwl90obua"/><stop offset="1" class="bldr2z22d"/></radialGradient><radialGradient id="iGgEtlP" cx="0" cy="0" r="1" gradientTransform="matrix(-.35586 -.16435 .16005 -.34654 4 18.736)" gradientUnits="userSpaceOnUse"><stop class="vwl90obua"/><stop offset="1" class="bldr2z22d"/></radialGradient><radialGradient id="icvwUCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.35586 -.16435 .16005 -.34654 4 22.736)" gradientUnits="userSpaceOnUse"><stop class="vwl90obua"/><stop offset="1" class="bldr2z22d"/></radialGradient><radialGradient id="idENW6b" cx="0" cy="0" r="1" gradientTransform="rotate(-152.186 13.222 2.623)scale(10.9581 6.44616)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="x-2or7j_t"/><stop offset="1" class="g_t0v3blp"/></radialGradient><radialGradient id="ikFRKAC" cx="0" cy="0" r="1" gradientTransform="rotate(-22.544 35.677 -19.503)scale(.89664 .73134)" gradientUnits="userSpaceOnUse"><stop class="q_3pfnbwa"/><stop offset="1" class="dx4zm6bfc"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tractor" /></template>
<style>
.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.acpf3dhmz {
  stop-color: var(--svg-color--1a9461, #1A9461);
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.bldr2z22d {
  stop-color: var(--svg-color--352938, #352938);
  stop-opacity: 0;
}

.c1qadxnxc {
  d: path("M3.507 21H2v-1h1.507c.276 0 .493.22.493.5c0 .27-.217.5-.493.5");
}

.c4lesxtds {
  stop-color: var(--svg-color--272859, #272859);
  stop-opacity: 0;
}

.cil3bopgu {
  stop-color: var(--svg-color--37c3da, #37C3DA);
  stop-opacity: 0;
}

.cx7ouchrx {
  cx: 7.704px;
  cy: 25.234px;
  r: 2.391px;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.cxnqgq3fm {
  fill: var(--svg-color--008461, #008461);
  d: path("M18 8h-1v7h1z");
}

.d7hv1zi4q {
  stop-color: var(--svg-color--293a5e, #293A5E);
  stop-opacity: 0;
}

.dksbgmbuv {
  stop-color: var(--svg-color--3e8f75, #3E8F75);
  stop-opacity: 0;
}

.dx4zm6bfc {
  stop-color: var(--svg-color--f0edf3, #F0EDF3);
  stop-opacity: 0;
}

.e2ix3g86r {
  stop-color: var(--svg-color--464274, #464274);
  stop-opacity: 0;
}

.eh_pno2_g {
  fill: var(--svg-color--153b3b, #153B3B);
  d: path("M27.656 16.467H24.46c-3.867 0-8.084 3.527-8.084 7.392c0 .276.443.108.719.108a.5.5 0 0 0 .5-.5c0-3.315 3.297-6.483 6.865-5.92l3.197.453z");
}

.f_rjqdbqn {
  cx: 24.907px;
  cy: 23.157px;
  r: 3.688px;
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.f6-f-cyvv {
  stop-color: var(--svg-color--392a49, #392A49);
}

.faa6ge4ul {
  d: path("M24.5 29.01a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11");
}

.ft5dv1b6b {
  fill: none;
}

.g_t0v3blp {
  stop-color: var(--svg-color--419f64, #419F64);
}

.hv1kl4b9t {
  stop-color: var(--svg-color--8c7d88, #8C7D88);
}

.is-42911n {
  stop-color: var(--svg-color--d6cde0, #D6CDE0);
}

.jk4iasb6y {
  stop-color: var(--svg-color--b4a5b9, #B4A5B9);
}

.jrlerbcbk {
  stop-color: var(--svg-color--8c7d88, #8C7D88);
  stop-opacity: 0;
}

.k4q-5y-mn {
  d: path("M3.507 23H2v-1h1.507c.276 0 .493.22.493.5c0 .27-.217.5-.493.5");
}

.k7r_24z4t {
  fill: var(--svg-color--153b3b, #153B3B);
  fill-rule: evenodd;
  d: path("M5.25 20.885a.5.5 0 0 1 .5-.5h2.288c2.487 0 4.5 2.014 4.5 4.5a.5.5 0 0 1-.5.5c-.663 0-1.022-.224-1.022-.5c0-1.934-1.567-3.307-3.5-3.307h-1.5c-.641 0-.766-.416-.766-.693");
}

.kkrvdacwk {
  stop-color: var(--svg-color--4bd780, #4BD780);
  stop-opacity: 0;
}

.kqor_bcjx {
  fill: var(--svg-color--268e6b, #268E6B);
  fill-rule: evenodd;
  d: path("M5.52 20.51a.5.5 0 0 1 .5-.5h2.49a4.5 4.5 0 0 1 4.5 4.5a.5.5 0 1 1-1 0c0-1.934-1.566-3.5-3.5-3.5H6.02a.5.5 0 0 1-.5-.5");
}

.kza2e647r {
  stop-color: var(--svg-color--293a5e, #293A5E);
}

.l0-x2wbul {
  stop-color: var(--svg-color--3e8f75, #3E8F75);
}

.m-a0bxj8c {
  width: 1.047px;
  height: 4.922px;
  x: 9.047px;
  y: 12.078px;
  rx: 0.523px;
}

.me_bxj91e {
  stop-color: var(--svg-color--00d263, #00D263);
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.mudrlubcd {
  stop-color: var(--svg-color--30144d, #30144D);
}

.n9st83e1z {
  stop-color: var(--svg-color--47d086, #47D086);
}

.nb0nml1qd {
  stop-color: var(--svg-color--4fea8c, #4FEA8C);
}

.o7n_asmpu {
  fill-rule: evenodd;
  d: path("M28 19H2v-.97C2 16.5 3.5 15 5 15h20.562A2.434 2.434 0 0 1 28 17.436z");
}

.o8fzkooti {
  stop-color: var(--svg-color--272859, #272859);
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.okv3qxu0i {
  d: path("M7.52 29.01a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.omw1x4odf {
  stop-color: var(--svg-color--36c570, #36C570);
  stop-opacity: 0;
}

.oqm4lik8g {
  fill: var(--svg-color--c8bbd6, #C8BBD6);
  d: path("M24.5 25.526a2.016 2.016 0 1 0 0-4.032a2.016 2.016 0 0 0 0 4.032");
}

.p20gbzbyi {
  stop-color: var(--svg-color--290941, #290941);
}

.p61s8ybxi {
  stop-color: var(--svg-color--464274, #464274);
}

.pq8bn39zf {
  stop-color: var(--svg-color--19965f, #19965F);
}

.q_3pfnbwa {
  stop-color: var(--svg-color--f0edf3, #F0EDF3);
}

.qah_rl9sc {
  stop-color: var(--svg-color--37bc6e, #37BC6E);
}

.qdmn3ybao {
  stop-color: var(--svg-color--392a49, #392A49);
  stop-opacity: 0;
}

.qkg33yihb {
  fill: var(--svg-color--ccbed9, #CCBED9);
  d: path("M7.52 26.784a1.273 1.273 0 1 0 0-2.547a1.273 1.273 0 0 0 0 2.547");
}

.qxuw3ub5w {
  stop-color: var(--svg-color--45f18a, #45F18A);
}

.rm_jcskye {
  d: path("M15.68 8L11 15h14V8z");
}

.s2blezbfa {
  stop-color: var(--svg-color--45f18a, #45F18A);
  stop-opacity: 0;
}

.s9kbc9bnf {
  fill: var(--svg-color--268e6b, #268E6B);
  fill-rule: evenodd;
  d: path("M23.99 17A5.99 5.99 0 0 0 18 23a.5.5 0 0 1-1 0c0-3.865 3.123-7 6.99-7h5.52a.5.5 0 0 1 0 1z");
}

.so0x8kiif {
  d: path("M14 7a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v1H15a1 1 0 0 1-1-1");
}

.t--w5zb2b {
  stop-color: var(--svg-color--4bd780, #4BD780);
}

.t4y6q3bin {
  fill-rule: evenodd;
  d: path("M5.52 20.51a.5.5 0 0 1 .5-.5h2.49a4.5 4.5 0 0 1 4.5 4.5a.5.5 0 1 1-1 0c0-1.934-1.566-3.5-3.5-3.5H6.02a.5.5 0 0 1-.5-.5");
}

.u_1m-kb6b {
  stop-color: var(--svg-color--46fafa, #46FAFA);
}

.uayemc_cg {
  stop-color: var(--svg-color--36c570, #36C570);
}

.uclgdjp3h {
  d: path("M3.507 19H2v-1h1.507c.276 0 .493.22.493.5s-.217.5-.493.5");
}

.ufft4gttv {
  stop-color: var(--svg-color--1a9461, #1A9461);
  stop-opacity: 0;
}

.uk3vqeb8o {
  stop-color: var(--svg-color--2a80d7, #2A80D7);
}

.uu_jpzz9d {
  stop-color: var(--svg-color--2066c3, #2066C3);
  stop-opacity: 0;
}

.v9lqhkqys {
  stop-color: var(--svg-color--744498, #744498);
}

.vwl90obua {
  stop-color: var(--svg-color--352938, #352938);
}

.vx0yhfpqp {
  fill-rule: evenodd;
  d: path("M23.99 17A5.99 5.99 0 0 0 18 23a.5.5 0 0 1-1 0c0-3.865 3.123-7 6.99-7h5.52a.5.5 0 0 1 0 1z");
}

.vx3snlb0l {
  stop-color: var(--svg-color--744498, #744498);
  stop-opacity: 0;
}

.whoc-y-6u {
  stop-color: var(--svg-color--1a0726, #1A0726);
}

.x_9c5iorj {
  stop-color: var(--svg-color--37c3da, #37C3DA);
}

.x-2or7j_t {
  stop-color: var(--svg-color--419f64, #419F64);
  stop-opacity: 0;
}

.xf8qojm2x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.469 22.656c.031-1.062.569-3.531 2.468-4.906s3.5-1.281 4.579-1.281H29.5");
}

.y327yp_8h {
  stop-color: var(--svg-color--2066c3, #2066C3);
}

.y537h1yla {
  fill: var(--svg-color--008461, #008461);
  d: path("M26 8h-1v9h1z");
}

.yhl16qbsu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.062 20.385h2.807c1.09.038 3.353.84 3.685 3.749");
}

.ylyfhvhfa {
  stop-color: var(--svg-color--44335c, #44335C);
}

.ztzradc6u {
  fill-rule: evenodd;
  d: path("M9.047 14.11v-.985h1.047v.985z");
}

.zxyrmxqdu {
  d: path("M25.562 15A2.434 2.434 0 0 1 28 17.436v5.82A2.745 2.745 0 0 1 25.252 26H3.998A2.003 2.003 0 0 1 2 24.004V18.03C2 16.5 3.5 15 5 15z");
}

</style>
