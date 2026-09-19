<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vbxy09bfu"/><path fill="url(#i0LyALb)" class="kzgs08axt"/><path fill="url(#i7GNgTL)" class="kzgs08axt"/><path class="owu4ddm3g"/><path fill="url(#ixYXelb)" class="z9fo_0wiw"/><path fill="url(#iRkhdqb)" class="z9fo_0wiw"/><g filter="url(#iiy9xdb)"><rect class="veeo5wsrd"/></g><g filter="url(#iHHImPd)"><rect class="zf6-ygwrz"/></g><path fill="url(#iyhAqae)" class="p_txsjm_i"/><path fill="url(#ilhz3Od)" class="lp207mbxb"/><path fill="url(#iNmBzZb)" class="lp207mbxb"/><path fill="url(#iIah3tW)" class="x_zqs-bia"/><path fill="url(#ik9qNWd)" class="hqqif6b7x"/><path fill="url(#iCZMbbe)" class="hqqif6b7x"/><path fill="url(#iMvr1Ed)" class="hqqif6b7x"/><g filter="url(#iTsWoMe)"><circle class="y6cn4bbni"/></g><g filter="url(#iYFcT0b)"><circle class="d54z0zbke"/></g><g filter="url(#iVpTiGe)"><circle class="yghz7pbss"/></g><g filter="url(#iXr2vHe)"><path stroke="url(#i8nBclb)" class="bb93h0wzc"/></g><g filter="url(#itOhRXc)"><path class="h5hsinqzm"/></g><g filter="url(#iCDDKZb)"><path stroke="url(#ivgfbFc)" class="yey8kcbgl"/></g><path fill="url(#iayVRve)" class="ygm9mfvig"/><g filter="url(#iAtyNEb)"><path fill="url(#igOLHRb)" class="gpp9co6ll"/></g><path fill="url(#iZxbG6d)" class="gpp9co6ll"/><g filter="url(#iFIORsd)"><path fill="url(#ieFQxPe)" class="gacovjiap"/><path fill="url(#ii0ycrb)" class="gacovjiap"/></g><path class="d90obob-u"/><path class="fkhhg_j2j"/><path class="trg_i58-v"/><path fill="url(#iuMwTAW)" class="zf-71gbyb"/><g filter="url(#i878mec)"><path fill="url(#ivy1AAd)" class="vukofgldd"/></g><path fill="url(#inkEYSc)" class="zdnoxyb5c"/><path fill="url(#i4ZQGvd)" class="rglnr4zgy"/><defs><linearGradient id="i0LyALb" x1="29.996" x2="29.125" y1="11.57" y2="20.758" gradientUnits="userSpaceOnUse"><stop class="nccrebb7c"/><stop offset="1" class="jcs-ok6ge"/></linearGradient><linearGradient id="i7GNgTL" x1="26.906" x2="26.906" y1="25.227" y2="22.258" gradientUnits="userSpaceOnUse"><stop class="ijvapkbrl"/><stop offset="1" class="ep3vyqxlk"/></linearGradient><linearGradient id="ixYXelb" x1="2.004" x2="4.509" y1="18.117" y2="18.117" gradientUnits="userSpaceOnUse"><stop class="riklp2bzg"/><stop offset="1" class="tc9xm-x5k"/></linearGradient><linearGradient id="iRkhdqb" x1="4.858" x2="4.858" y1="25.312" y2="21.824" gradientUnits="userSpaceOnUse"><stop class="r8urb72zb"/><stop offset="1" class="x-lq3kevb"/></linearGradient><linearGradient id="iyhAqae" x1="23.531" x2="9" y1="8.695" y2="8.695" gradientUnits="userSpaceOnUse"><stop class="gv6aetk5b"/><stop offset="1" class="u1wzc6w5j"/></linearGradient><linearGradient id="ilhz3Od" x1="9.063" x2="9.063" y1="10.258" y2="7.883" gradientUnits="userSpaceOnUse"><stop offset=".105" class="mh9-etr6a"/><stop offset="1" class="v9buq5z0c"/></linearGradient><linearGradient id="iNmBzZb" x1="10.039" x2="9.832" y1="9.68" y2="9.68" gradientUnits="userSpaceOnUse"><stop class="rk8-ezbnk"/><stop offset=".971" class="vm79q5bvy"/></linearGradient><linearGradient id="iIah3tW" x1="16" x2="16" y1="2.023" y2="10.133" gradientUnits="userSpaceOnUse"><stop class="crbfad6bo"/><stop offset="1" class="x-h8x3bml"/></linearGradient><linearGradient id="ik9qNWd" x1="26.031" x2="6.313" y1="16.883" y2="16.883" gradientUnits="userSpaceOnUse"><stop class="g_ki--b6g"/><stop offset=".949" class="d3-fsbc6n"/></linearGradient><linearGradient id="iCZMbbe" x1="26.373" x2="26.27" y1="18.195" y2="18.195" gradientUnits="userSpaceOnUse"><stop offset=".132" class="dj-fw5b_x"/><stop offset="1" class="eoo9ekbwn"/></linearGradient><linearGradient id="iMvr1Ed" x1="5.627" x2="5.766" y1="18.07" y2="18.07" gradientUnits="userSpaceOnUse"><stop class="fmm-xccns"/><stop offset="1" class="i9s9p5bzh"/></linearGradient><linearGradient id="i8nBclb" x1="13.711" x2="14.188" y1="17.961" y2="16.523" gradientUnits="userSpaceOnUse"><stop offset=".199" class="j7eg1nc5x"/><stop offset="1" class="a7r52qtms"/></linearGradient><linearGradient id="ivgfbFc" x1="16" x2="16" y1="20.055" y2="24.055" gradientUnits="userSpaceOnUse"><stop class="y8mlacb1f"/><stop offset="1" class="tzga4zbda"/></linearGradient><linearGradient id="iayVRve" x1="16" x2="16" y1="20.055" y2="25.012" gradientUnits="userSpaceOnUse"><stop class="mbwkdhban"/><stop offset="1" class="fg43lhafd"/></linearGradient><linearGradient id="igOLHRb" x1="11.344" x2="22.094" y1="27.914" y2="27.852" gradientUnits="userSpaceOnUse"><stop class="uor5s7gvk"/><stop offset="1" class="fniz64iaz"/></linearGradient><linearGradient id="iZxbG6d" x1="16" x2="16" y1="19.695" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="xtfj0pb3a"/><stop offset="1" class="x4o870bcm"/></linearGradient><linearGradient id="ieFQxPe" x1="16" x2="16" y1="20.055" y2="27.977" gradientUnits="userSpaceOnUse"><stop class="s_fkwccyi"/><stop offset="1" class="z5s0yzqsp"/></linearGradient><linearGradient id="ii0ycrb" x1="16" x2="16" y1="19.884" y2="21.78" gradientUnits="userSpaceOnUse"><stop offset=".163" class="my0z6clib"/><stop offset="1" class="giycflk_q"/></linearGradient><linearGradient id="iuMwTAW" x1="16" x2="16" y1="20.919" y2="21.586" gradientUnits="userSpaceOnUse"><stop class="p1zv74cmn"/><stop offset="1" class="nj9g0kd6q"/></linearGradient><linearGradient id="ivy1AAd" x1="9.478" x2="23.653" y1="11.175" y2="11.175" gradientUnits="userSpaceOnUse"><stop class="w_bp7yv-d"/><stop offset="1" class="d8nnz-bbn"/></linearGradient><linearGradient id="inkEYSc" x1="5.969" x2="5.969" y1="25.012" y2="23.602" gradientUnits="userSpaceOnUse"><stop offset=".077" class="o6z0hwbnn"/><stop offset="1" class="hlmxe-bye"/></linearGradient><linearGradient id="i4ZQGvd" x1="26.031" x2="26.031" y1="25.012" y2="23.602" gradientUnits="userSpaceOnUse"><stop offset=".077" class="gi-pssv3g"/><stop offset="1" class="q44o-8bnd"/></linearGradient><filter id="iiy9xdb" width="12.623" height="15.041" x="17.364" y="9.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19569" stdDeviation=".4"/></filter><filter id="iHHImPd" width="12.623" height="15.041" x="1.923" y="9.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19569" stdDeviation=".4"/></filter><filter id="iTsWoMe" width="2.084" height="2.084" x="26.848" y="16.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.486275 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19569"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19569" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.03" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.721569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19569"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.466667 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19569" result="effect3_innerShadow_18_19569"/></filter><filter id="iYFcT0b" width="2.084" height="2.084" x="26.848" y="19.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.454902 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19569"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19569" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.03" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.721569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19569"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.427451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19569" result="effect3_innerShadow_18_19569"/></filter><filter id="iVpTiGe" width="2.084" height="2.084" x="26.848" y="22.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.454902 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19569"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19569" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.03" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.431373 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19569"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.247059 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19569" result="effect3_innerShadow_18_19569"/></filter><filter id="iXr2vHe" width="6.755" height="2.231" x="12.623" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19569" stdDeviation=".025"/></filter><filter id="itOhRXc" width="6.655" height="2.181" x="12.623" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.105882 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19569"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.121569 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19569" result="effect2_innerShadow_18_19569"/></filter><filter id="iCDDKZb" width="18.078" height="5.208" x="6.961" y="19.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19569" stdDeviation=".025"/></filter><filter id="iAtyNEb" width="14.022" height="9.953" x="8.989" y="20.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.298039 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19569"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.219608 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19569" result="effect2_innerShadow_18_19569"/></filter><filter id="iFIORsd" width="12.4" height="8.322" x="9.8" y="19.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19569"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19569" result="shape"/></filter><filter id="i878mec" width="20.469" height="1.469" x="5.766" y="10.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19569" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:printer" /></template>
<style>
.a7r52qtms {
  stop-color: var(--svg-color--4b3580, #4B3580);
}

.bb93h0wzc {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.723 17.016c0-.561.454-1.016 1.015-1.016h4.524a1.016 1.016 0 0 1 0 2.031h-4.524c-.56 0-1.015-.454-1.015-1.015Z");
}

.crbfad6bo {
  stop-color: var(--svg-color--e2d9eb, #E2D9EB);
}

.d3-fsbc6n {
  stop-color: var(--svg-color--5a407b, #5A407B);
}

.d54z0zbke {
  cx: 27.99px;
  cy: 20.004px;
  r: 0.842px;
  fill: var(--svg-color--958e9d, #958E9D);
}

.d8nnz-bbn {
  stop-color: var(--svg-color--615aae, #615AAE);
}

.d90obob-u {
  fill: var(--svg-color--b8b1be, #B8B1BE);
  d: path("M11.82 25.495c0-.267.216-.483.482-.483h7.396a.482.482 0 1 1 0 .965h-7.396a.48.48 0 0 1-.482-.483");
}

.dj-fw5b_x {
  stop-color: var(--svg-color--625ca5, #625CA5);
}

.eoo9ekbwn {
  stop-color: var(--svg-color--625ca5, #625CA5);
  stop-opacity: 0;
}

.ep3vyqxlk {
  stop-color: var(--svg-color--c6bbd3, #C6BBD3);
  stop-opacity: 0;
}

.fg43lhafd {
  stop-color: var(--svg-color--1c142e, #1C142E);
}

.fkhhg_j2j {
  fill: var(--svg-color--b2acb8, #B2ACB8);
  d: path("M11.82 23.448c0-.267.216-.482.482-.482h7.396a.482.482 0 1 1 0 .964h-7.396a.48.48 0 0 1-.482-.482");
}

.fmm-xccns {
  stop-color: var(--svg-color--44325e, #44325E);
}

.fniz64iaz {
  stop-color: var(--svg-color--4a4668, #4A4668);
}

.ft5dv1b6b {
  fill: none;
}

.g_ki--b6g {
  stop-color: var(--svg-color--5c55ab, #5C55AB);
}

.gacovjiap {
  d: path("M10 20.055h12v6.122a1.8 1.8 0 0 1-1.8 1.8h-8.4a1.8 1.8 0 0 1-1.8-1.8z");
}

.gi-pssv3g {
  stop-color: var(--svg-color--4b3a96, #4B3A96);
}

.giycflk_q {
  stop-color: var(--svg-color--a198ad, #A198AD);
  stop-opacity: 0;
}

.gpp9co6ll {
  d: path("M9.04 20.064q.097-.01.196-.01h13.528q.1 0 .197.01v7.768c0 1.174-.895 2.126-2 2.126h-9.922c-1.105 0-2-.952-2-2.126z");
}

.gv6aetk5b {
  stop-color: var(--svg-color--5b54a3, #5B54A3);
}

.h5hsinqzm {
  fill: var(--svg-color--403756, #403756);
  d: path("M12.723 17.016c0-.561.454-1.016 1.015-1.016h4.524a1.016 1.016 0 0 1 0 2.031h-4.524c-.56 0-1.015-.454-1.015-1.015");
}

.hlmxe-bye {
  stop-color: var(--svg-color--4a2d6e, #4A2D6E);
  stop-opacity: 0;
}

.hqqif6b7x {
  d: path("M5.627 10.027a.1.1 0 0 1 .1-.1h20.546a.1.1 0 0 1 .1.1v14.886a.1.1 0 0 1-.1.1H5.727a.1.1 0 0 1-.1-.1z");
}

.i9s9p5bzh {
  stop-color: var(--svg-color--44325e, #44325E);
  stop-opacity: 0;
}

.ijvapkbrl {
  stop-color: var(--svg-color--9e84b7, #9E84B7);
}

.j7eg1nc5x {
  stop-color: var(--svg-color--69578a, #69578A);
}

.jcs-ok6ge {
  stop-color: var(--svg-color--ebe7ee, #EBE7EE);
  stop-opacity: 0;
}

.kzgs08axt {
  d: path("M26.373 10.027a.1.1 0 0 1 .1-.1h1.323a2.2 2.2 0 0 1 2.2 2.2v10.686a2.2 2.2 0 0 1-2.2 2.2h-1.323a.1.1 0 0 1-.1-.1z");
}

.lp207mbxb {
  d: path("M15 4.102h-4.566a2.2 2.2 0 0 0-2.2 2.2v8.08H15z");
}

.mbwkdhban {
  stop-color: var(--svg-color--140c25, #140C25);
}

.mh9-etr6a {
  stop-color: var(--svg-color--503b6a, #503B6A);
}

.my0z6clib {
  stop-color: var(--svg-color--776987, #776987);
}

.nccrebb7c {
  stop-color: var(--svg-color--ebe7ee, #EBE7EE);
}

.nj9g0kd6q {
  stop-color: var(--svg-color--8a8491, #8A8491);
  stop-opacity: 0;
}

.o6z0hwbnn {
  stop-color: var(--svg-color--4a2d6e, #4A2D6E);
}

.owu4ddm3g {
  fill: var(--svg-color--cfc4d5, #CFC4D5);
  d: path("M5.627 10.027a.1.1 0 0 0-.1-.1H4.204a2.2 2.2 0 0 0-2.2 2.2v10.686a2.2 2.2 0 0 0 2.2 2.2h1.323a.1.1 0 0 0 .1-.1z");
}

.p_txsjm_i {
  d: path("M8.234 6.302a2.2 2.2 0 0 1 2.2-2.2h11.132a2.2 2.2 0 0 1 2.2 2.2v8.08H8.234z");
}

.p1zv74cmn {
  stop-color: var(--svg-color--8a8491, #8A8491);
}

.q44o-8bnd {
  stop-color: var(--svg-color--4b3a96, #4B3A96);
  stop-opacity: 0;
}

.r8urb72zb {
  stop-color: var(--svg-color--947bab, #947BAB);
}

.rglnr4zgy {
  d: path("M24.914 25.013h1.359a.1.1 0 0 0 .1-.1v-3.994h-1.459z");
}

.riklp2bzg {
  stop-color: var(--svg-color--8b8690, #8B8690);
}

.rk8-ezbnk {
  stop-color: var(--svg-color--473361, #473361);
}

.s_fkwccyi {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
}

.tc9xm-x5k {
  stop-color: var(--svg-color--8b8690, #8B8690);
  stop-opacity: 0;
}

.trg_i58-v {
  fill: var(--svg-color--a19ca7, #A19CA7);
  d: path("M11.82 21.4c0-.265.216-.481.482-.481h7.396a.482.482 0 1 1 0 .964h-7.396a.48.48 0 0 1-.482-.482");
}

.tzga4zbda {
  stop-color: var(--svg-color--4e3682, #4E3682);
  stop-opacity: 0;
}

.u1wzc6w5j {
  stop-color: var(--svg-color--584076, #584076);
}

.uor5s7gvk {
  stop-color: var(--svg-color--5d447c, #5D447C);
}

.v9buq5z0c {
  stop-color: var(--svg-color--503b6a, #503B6A);
  stop-opacity: 0;
}

.vbxy09bfu {
  fill: var(--svg-color--d8d0de, #D8D0DE);
  d: path("M26.373 10.027a.1.1 0 0 1 .1-.1h1.323a2.2 2.2 0 0 1 2.2 2.2v10.686a2.2 2.2 0 0 1-2.2 2.2h-1.323a.1.1 0 0 1-.1-.1z");
}

.veeo5wsrd {
  width: 11.023px;
  height: 13.441px;
  x: 18.164px;
  y: 10.695px;
  fill: var(--svg-color--c9c0d3, #C9C0D3);
  rx: 1.25px;
}

.vm79q5bvy {
  stop-color: var(--svg-color--473361, #473361);
  stop-opacity: 0;
}

.vukofgldd {
  d: path("M6.266 10.519h19.469v.469H6.266z");
}

.w_bp7yv-d {
  stop-color: var(--svg-color--5e457d, #5E457D);
}

.x_zqs-bia {
  d: path("M10 3.823a1.8 1.8 0 0 1 1.8-1.8h8.4a1.8 1.8 0 0 1 1.8 1.8v10.56H10z");
}

.x-h8x3bml {
  stop-color: var(--svg-color--cec9d5, #CEC9D5);
}

.x-lq3kevb {
  stop-color: var(--svg-color--947bab, #947BAB);
  stop-opacity: 0;
}

.x4o870bcm {
  stop-color: var(--svg-color--1f0c35, #1F0C35);
  stop-opacity: 0;
}

.xtfj0pb3a {
  stop-color: var(--svg-color--1f0c35, #1F0C35);
}

.y6cn4bbni {
  cx: 27.99px;
  cy: 17.035px;
  r: 0.842px;
  fill: var(--svg-color--958e9d, #958E9D);
}

.y8mlacb1f {
  stop-color: var(--svg-color--4e3682, #4E3682);
}

.yey8kcbgl {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.914 25.013H7.086v-2.808a2.15 2.15 0 0 1 2.15-2.15h13.528a2.15 2.15 0 0 1 2.15 2.15z");
}

.yghz7pbss {
  cx: 27.99px;
  cy: 23.004px;
  r: 0.842px;
  fill: var(--svg-color--ef315a, #EF315A);
}

.ygm9mfvig {
  d: path("M24.914 25.013H7.086v-2.808a2.15 2.15 0 0 1 2.15-2.15h13.528a2.15 2.15 0 0 1 2.15 2.15z");
}

.z5s0yzqsp {
  stop-color: var(--svg-color--ece3f6, #ECE3F6);
}

.z9fo_0wiw {
  d: path("M5.627 10.027a.1.1 0 0 0-.1-.1H4.204a2.2 2.2 0 0 0-2.2 2.2v10.686a2.2 2.2 0 0 0 2.2 2.2h1.323a.1.1 0 0 0 .1-.1z");
}

.zdnoxyb5c {
  d: path("M7.086 25.013H5.727a.1.1 0 0 1-.1-.1v-3.994h1.459z");
}

.zf-71gbyb {
  d: path("M11.82 21.4c0-.265.216-.481.482-.481h7.396a.482.482 0 1 1 0 .964h-7.396a.48.48 0 0 1-.482-.482");
}

.zf6-ygwrz {
  width: 11.023px;
  height: 13.441px;
  x: 2.723px;
  y: 10.695px;
  fill: var(--svg-color--bfb6c8, #BFB6C8);
  rx: 1.25px;
}

</style>
