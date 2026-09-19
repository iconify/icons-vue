<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ia3R7Ug)" class="mbf5b3b4y"/><path fill="url(#iQmCh3d)" class="mbf5b3b4y"/><g filter="url(#iQjwvvb)"><path fill="url(#i3lRP1d)" class="a6ftoy7qg"/></g><g filter="url(#iM8fR0d)"><path fill="url(#i2eGoTb)" class="xyb04qkou"/></g><g filter="url(#iGBbnYQ)"><path fill="url(#i0zWZ1c)" class="gi-vdlbvn"/><path fill="url(#iSObRGc)" class="gi-vdlbvn"/></g><g filter="url(#iRLRzbd)"><path fill="url(#iwXF45c)" class="dlv-z1pdc"/><path fill="url(#imE8pNd)" class="dlv-z1pdc"/><path fill="url(#ioDmvsb)" class="dlv-z1pdc"/><path fill="url(#iVJeJvb)" class="dlv-z1pdc"/><path fill="url(#ispWmKe)" class="dlv-z1pdc"/><path fill="url(#ig0aAab)" class="dlv-z1pdc"/><path fill="url(#idBKAkb)" class="dlv-z1pdc"/></g><g filter="url(#iv4z6Cq)"><path stroke="url(#iNsGgAe)" class="dlugfutdo"/></g><path class="mj-lwkb9n"/><path fill="url(#iHxTO2b)" class="r05s05bjl"/><g filter="url(#ipPAnOb)"><path class="s4m5hpbxf"/></g><path fill="url(#iVjVnfe)" class="w7642ybaq"/><path fill="url(#icExWcd)" class="w7642ybaq"/><g filter="url(#iUNwr8d)"><path stroke="url(#ih1qged)" class="eariphb8f"/></g><g filter="url(#iac1Vuc)"><path class="pkb_a_bai"/><path fill="url(#irJYkDd)" class="k13qmn6xf"/><path fill="url(#ifBobew)" class="k13qmn6xf"/></g><g filter="url(#iE08KVd)"><path stroke="url(#ip4qNZi)" class="zykhhrb2i"/></g><path fill="url(#iVGrgBc)" class="dzawkn4-g"/><g filter="url(#iDLozXd)"><path stroke="url(#iV4p3Ob)" class="oftc7sneh"/></g><path fill="url(#iyc9Gqe)" class="tthlbdnfh"/><path fill="url(#ijrWcxe)" class="lu95rbbll"/><path fill="url(#in8To5b)" class="lu95rbbll"/><path fill="url(#iXzpZnd)" class="lu95rbbll"/><path fill="url(#i8qtK7Q)" class="lu95rbbll"/><path fill="url(#isqeI8c)" class="lu95rbbll"/><g filter="url(#iIWQXpe)"><path fill="url(#itsZqEd)" class="g52hn4bfq"/><path fill="url(#icYKM0b)" class="g52hn4bfq"/></g><path fill="url(#i9hwGLc)" class="vggt17bvc"/><path fill="url(#iok9Dyb)" class="k-rs5qyxt"/><path fill="url(#i3L1jMp)" class="k-rs5qyxt"/><path fill="url(#i2MPtFe)" class="q026igb2j"/><path fill="url(#iVOqE7d)" class="q026igb2j"/><path fill="url(#i0b220P)" class="q026igb2j"/><path fill="url(#iWFZVfF)" class="q026igb2j"/><path fill="url(#iZ64zsB)" class="q026igb2j"/><path fill="url(#iscDvcb)" class="vwi6usgxw"/><path fill="url(#ilbc3ve)" class="vwi6usgxw"/><defs><linearGradient id="ia3R7Ug" x1="7.453" x2="6" y1="16.994" y2="16.494" gradientUnits="userSpaceOnUse"><stop offset=".382" class="qkfquqbuk"/><stop offset=".865" class="oyxxcxf0e"/></linearGradient><linearGradient id="iQmCh3d" x1="5.961" x2="6.103" y1="17.277" y2="17.277" gradientUnits="userSpaceOnUse"><stop class="sugqmswmx"/><stop offset="1" class="bslru85hd"/></linearGradient><linearGradient id="i3lRP1d" x1="6.604" x2="9.244" y1="27.015" y2="27.015" gradientUnits="userSpaceOnUse"><stop class="dwjy1_hjr"/><stop offset="1" class="dxjef_7ed"/></linearGradient><linearGradient id="i2eGoTb" x1="22.604" x2="25.244" y1="27.015" y2="27.015" gradientUnits="userSpaceOnUse"><stop class="dwjy1_hjr"/><stop offset="1" class="dxjef_7ed"/></linearGradient><linearGradient id="i0zWZ1c" x1="24.381" x2="25.678" y1="15.872" y2="18.682" gradientUnits="userSpaceOnUse"><stop class="xc4v0fmgz"/><stop offset="1" class="gej7obcef"/></linearGradient><linearGradient id="iwXF45c" x1="16.003" x2="16.003" y1="18.454" y2="25.433" gradientUnits="userSpaceOnUse"><stop class="g_sgy9b-w"/><stop offset="1" class="p6ulpsban"/></linearGradient><linearGradient id="imE8pNd" x1="16" x2="16" y1="26.02" y2="23.948" gradientUnits="userSpaceOnUse"><stop class="o2molzbye"/><stop offset="1" class="mokyx3xtu"/></linearGradient><linearGradient id="ioDmvsb" x1="4.37" x2="8.789" y1="23.161" y2="23.161" gradientUnits="userSpaceOnUse"><stop class="jv8m1-b5o"/><stop offset="1" class="v0uy6qf0b"/></linearGradient><linearGradient id="iVJeJvb" x1="4.787" x2="5.538" y1="21.673" y2="21.673" gradientUnits="userSpaceOnUse"><stop class="zekaiwv8e"/><stop offset="1" class="qivwlr5pk"/></linearGradient><linearGradient id="iNsGgAe" x1="26.687" x2="25.094" y1="19.885" y2="23.119" gradientUnits="userSpaceOnUse"><stop class="uh6fg5_ca"/><stop offset="1" class="di19a9x6c"/></linearGradient><linearGradient id="icExWcd" x1="5" x2="5.375" y1="21.916" y2="21.916" gradientUnits="userSpaceOnUse"><stop class="rnewovgur"/><stop offset="1" class="zkq5yhpha"/></linearGradient><linearGradient id="ih1qged" x1="16.578" x2="16.123" y1="22.01" y2="23.862" gradientUnits="userSpaceOnUse"><stop offset=".574" class="iwdasb5yv"/><stop offset="1" class="k79pnpmsk"/></linearGradient><linearGradient id="irJYkDd" x1="12" x2="13.122" y1="23.01" y2="23.01" gradientUnits="userSpaceOnUse"><stop class="v-o1r-i4x"/><stop offset="1" class="hkhj7kbuq"/></linearGradient><linearGradient id="ifBobew" x1="20.193" x2="18.801" y1="23.01" y2="23.01" gradientUnits="userSpaceOnUse"><stop class="yhbaaxbfb"/><stop offset="1" class="ky20_0v4t"/></linearGradient><linearGradient id="ip4qNZi" x1="10.134" x2="9.42" y1="22.122" y2="22.855" gradientUnits="userSpaceOnUse"><stop class="t2v98obvb"/><stop offset="1" class="di19a9x6c"/></linearGradient><linearGradient id="iVGrgBc" x1="10" x2="10" y1="21.823" y2="23.01" gradientUnits="userSpaceOnUse"><stop class="zf7g7gb1d"/><stop offset="1" class="btxpjlbvu"/></linearGradient><linearGradient id="iV4p3Ob" x1="22.134" x2="21.42" y1="22.122" y2="22.855" gradientUnits="userSpaceOnUse"><stop class="t2v98obvb"/><stop offset="1" class="di19a9x6c"/></linearGradient><linearGradient id="iyc9Gqe" x1="22" x2="22" y1="21.823" y2="23.01" gradientUnits="userSpaceOnUse"><stop class="zf7g7gb1d"/><stop offset="1" class="btxpjlbvu"/></linearGradient><linearGradient id="ijrWcxe" x1="14.875" x2="14.875" y1="11.697" y2="17.323" gradientUnits="userSpaceOnUse"><stop class="ongrvfd6a"/><stop offset="1" class="cp65m-qgt"/></linearGradient><linearGradient id="in8To5b" x1="16" x2="16" y1="11.885" y2="13.26" gradientUnits="userSpaceOnUse"><stop class="tfsvxmcqs"/><stop offset="1" class="v_xlxgp3p"/></linearGradient><linearGradient id="i8qtK7Q" x1="7.729" x2="7.902" y1="14.816" y2="14.858" gradientUnits="userSpaceOnUse"><stop class="datmogb6v"/><stop offset="1" class="eaeu4sxep"/></linearGradient><linearGradient id="isqeI8c" x1="24.469" x2="24.195" y1="15.541" y2="15.604" gradientUnits="userSpaceOnUse"><stop offset=".313" class="ajietmbyg"/><stop offset="1" class="ka1fgb3yy"/></linearGradient><linearGradient id="itsZqEd" x1="13.125" x2="23.495" y1="11.014" y2="11.014" gradientUnits="userSpaceOnUse"><stop class="ndmn59b4d"/><stop offset="1" class="je3cv5bry"/></linearGradient><linearGradient id="icYKM0b" x1="16" x2="16" y1="10.02" y2="10.604" gradientUnits="userSpaceOnUse"><stop class="a0v1a5bcw"/><stop offset="1" class="semze1bzv"/></linearGradient><linearGradient id="i9hwGLc" x1="12" x2="15.757" y1="8.015" y2="8.015" gradientUnits="userSpaceOnUse"><stop class="v2qzbu00p"/><stop offset=".233" class="znpxxobat"/></linearGradient><linearGradient id="iok9Dyb" x1="17.125" x2="20.003" y1="8.015" y2="8.015" gradientUnits="userSpaceOnUse"><stop class="wrovydbnd"/><stop offset="1" class="e1jv8qb_w"/></linearGradient><linearGradient id="iVOqE7d" x1="16" x2="16" y1="7.01" y2="7.268" gradientUnits="userSpaceOnUse"><stop class="rnyxtsb4p"/><stop offset="1" class="qqmsgjorc"/></linearGradient><linearGradient id="i0b220P" x1="12" x2="13.219" y1="9.823" y2="9.823" gradientUnits="userSpaceOnUse"><stop class="phlxq0fyq"/><stop offset="1" class="rjwtwdbcs"/></linearGradient><linearGradient id="iWFZVfF" x1="20.781" x2="19.469" y1="9.823" y2="9.823" gradientUnits="userSpaceOnUse"><stop class="phlxq0fyq"/><stop offset="1" class="rjwtwdbcs"/></linearGradient><linearGradient id="iscDvcb" x1="16" x2="16" y1="17.742" y2="20.01" gradientUnits="userSpaceOnUse"><stop class="soczd1nzu"/><stop offset="1" class="wwykkk7vx"/></linearGradient><linearGradient id="ilbc3ve" x1="16" x2="16" y1="17.94" y2="18.26" gradientUnits="userSpaceOnUse"><stop class="qo7ff_bqw"/><stop offset="1" class="sn6nsmb7j"/></linearGradient><filter id="iQjwvvb" width="4" height="4" x="6" y="25.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.329412 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10256"/></filter><filter id="iM8fR0d" width="4" height="4" x="22" y="25.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.329412 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10256"/></filter><filter id="iGBbnYQ" width="4.48" height="3.1" x="21.52" y="16.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.92549 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10256"/></filter><filter id="iRLRzbd" width="22" height="8.15" x="5" y="17.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.396078 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10256"/></filter><filter id="iv4z6Cq" width="3.159" height="3.3" x="23.85" y="19.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10256" stdDeviation=".05"/></filter><filter id="ipPAnOb" width="3.206" height="3.3" x="4.944" y="19.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10256" stdDeviation=".05"/></filter><filter id="iUNwr8d" width="8.29" height="2.3" x="11.85" y="20.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10256" stdDeviation=".05"/></filter><filter id="iac1Vuc" width="7.99" height="2.4" x="12" y="21.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.443137 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10256"/></filter><filter id="iE08KVd" width="2.3" height="2.3" x="8.85" y="20.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10256" stdDeviation=".05"/></filter><filter id="iDLozXd" width="2.3" height="2.3" x="20.85" y="20.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10256" stdDeviation=".05"/></filter><filter id="iIWQXpe" width="15.48" height="2" x="8.26" y="10.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.513726 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10256"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.254902 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10256" result="effect2_innerShadow_18_10256"/></filter><radialGradient id="iSObRGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 .9375 -.2998 -.26981 26.11 15.9)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="qnoj66lkr"/><stop offset="1" class="ov5m9o98p"/></radialGradient><radialGradient id="ispWmKe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18038 1.80505 -.63623 -.76852 26.484 19.565)" gradientUnits="userSpaceOnUse"><stop class="dz-j57b_w"/><stop offset="1" class="t2i_cg0dh"/></radialGradient><radialGradient id="ig0aAab" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.93099 -1.1438 0 25.983 21.495)" gradientUnits="userSpaceOnUse"><stop class="dz-j57b_w"/><stop offset="1" class="t2i_cg0dh"/></radialGradient><radialGradient id="idBKAkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78719 -4.91477 0 8.254 17.134)" gradientUnits="userSpaceOnUse"><stop class="rml5bzb6o"/><stop offset="1" class="ffgihtorj"/></radialGradient><radialGradient id="iHxTO2b" cx="0" cy="0" r="1" gradientTransform="rotate(144.058 9.696 14.03)scale(3.0879 1.53072)" gradientUnits="userSpaceOnUse"><stop class="wvqs8wszw"/><stop offset="1" class="a_cyghbeb"/></radialGradient><radialGradient id="iVjVnfe" cx="0" cy="0" r="1" gradientTransform="matrix(3.15625 0 0 2.78125 5 21.635)" gradientUnits="userSpaceOnUse"><stop class="j5a_8iwoa"/><stop offset="1" class="z4hq-cbry"/></radialGradient><radialGradient id="iXzpZnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96875 2.14063 -.76785 -.7062 24.39 11.87)" gradientUnits="userSpaceOnUse"><stop offset=".389" class="bvtziwflf"/><stop offset="1" class="q0ns1qj7n"/></radialGradient><radialGradient id="i3L1jMp" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.73437 -.73803 0 19.547 8.088)" gradientUnits="userSpaceOnUse"><stop class="yqv10n6gc"/><stop offset="1" class="vridjdb8x"/></radialGradient><radialGradient id="i2MPtFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.19131 9.31103 0 16 10.201)" gradientUnits="userSpaceOnUse"><stop class="todd_ybti"/><stop offset="1" class="majhx5b9s"/></radialGradient><radialGradient id="iZ64zsB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.375 1.5625 0 17.969 10.197)" gradientUnits="userSpaceOnUse"><stop class="h7y6ud_8j"/><stop offset="1" class="s86h-zbdj"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-police-car" /></template>
<style>
.a_cyghbeb {
  stop-color: var(--svg-color--e7c04b, #E7C04B);
  stop-opacity: 0;
}

.a0v1a5bcw {
  stop-color: var(--svg-color--666668, #666668);
}

.a6ftoy7qg {
  d: path("M9 29.01H7c-.55 0-1-.45-1-1v-3h4v3c0 .56-.44 1-1 1");
}

.ajietmbyg {
  stop-color: var(--svg-color--76eaff, #76EAFF);
}

.bslru85hd {
  stop-color: var(--svg-color--a6a2aa, #A6A2AA);
  stop-opacity: 0;
}

.btxpjlbvu {
  stop-color: var(--svg-color--d80e26, #D80E26);
}

.bvtziwflf {
  stop-color: var(--svg-color--1bbcee, #1BBCEE);
}

.cp65m-qgt {
  stop-color: var(--svg-color--4cf0f8, #4CF0F8);
}

.datmogb6v {
  stop-color: var(--svg-color--3bb7eb, #3BB7EB);
}

.di19a9x6c {
  stop-color: var(--svg-color--565456, #565456);
}

.dlugfutdo {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24 22.01c0 .55.429 1 .953 1h1.906v-3h-1.906c-.524 0-.953.45-.953 1z");
}

.dlv-z1pdc {
  d: path("M27 20.03c0-.62-.35-1.19-.91-1.46l-1.13-.55H7.04l-1.13.55c-.56.27-.91.84-.91 1.46v3.99c0 1.1.9 2 2 2h17.99c1.1 0 2-.9 2-2H27z");
}

.dwjy1_hjr {
  stop-color: var(--svg-color--361752, #361752);
}

.dxjef_7ed {
  stop-color: var(--svg-color--2d1e3b, #2D1E3B);
}

.dz-j57b_w {
  stop-color: var(--svg-color--7f7e7f, #7F7E7F);
}

.dzawkn4-g {
  d: path("M10 23.01a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.e1jv8qb_w {
  stop-color: var(--svg-color--f43563, #F43563);
}

.eaeu4sxep {
  stop-color: var(--svg-color--3bb7eb, #3BB7EB);
  stop-opacity: 0;
}

.eariphb8f {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19 21.01h-6c-.55 0-1 .45-1 1s.45 1 1 1h5.99c.55 0 1-.45 1-1c.01-.55-.43-1-.99-1Z");
}

.ffgihtorj {
  stop-color: var(--svg-color--616972, #616972);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g_sgy9b-w {
  stop-color: var(--svg-color--535254, #535254);
}

.g52hn4bfq {
  d: path("m8.54 11.89l-.03.13h14.98l-.03-.13a2.46 2.46 0 0 0-2.39-1.87H10.93a2.45 2.45 0 0 0-2.39 1.87");
}

.gej7obcef {
  stop-color: var(--svg-color--949297, #949297);
}

.gi-vdlbvn {
  d: path("M25.13 19.01h-3.61v-.66c0-1.29 1.05-2.34 2.34-2.34h1.28c.48 0 .86.39.86.86v1.28c0 .48-.39.86-.87.86");
}

.h7y6ud_8j {
  stop-color: var(--svg-color--c8c5c8, #C8C5C8);
}

.hkhj7kbuq {
  stop-color: var(--svg-color--b4afb7, #B4AFB7);
  stop-opacity: 0;
}

.iwdasb5yv {
  stop-color: var(--svg-color--2e2c2f, #2E2C2F);
}

.j5a_8iwoa {
  stop-color: var(--svg-color--ffeb73, #FFEB73);
}

.je3cv5bry {
  stop-color: var(--svg-color--585659, #585659);
}

.jv8m1-b5o {
  stop-color: var(--svg-color--252426, #252426);
}

.k-rs5qyxt {
  d: path("M19 7.01c.55 0 1 .45 1 1v1h-4v-2z");
}

.k13qmn6xf {
  d: path("M19 21.01h-6c-.55 0-1 .45-1 1s.45 1 1 1h5.99c.55 0 1-.45 1-1c.01-.55-.43-1-.99-1");
}

.k79pnpmsk {
  stop-color: var(--svg-color--6b6a6c, #6B6A6C);
}

.ka1fgb3yy {
  stop-color: var(--svg-color--76eaff, #76EAFF);
  stop-opacity: 0;
}

.ky20_0v4t {
  stop-color: var(--svg-color--716875, #716875);
  stop-opacity: 0;
}

.lu95rbbll {
  d: path("M21.07 10.01H10.93c-1.13 0-2.12.77-2.39 1.87l-1.51 6.13h17.94l-1.51-6.13a2.46 2.46 0 0 0-2.39-1.87");
}

.majhx5b9s {
  stop-color: var(--svg-color--e8e5ea, #E8E5EA);
}

.mbf5b3b4y {
  d: path("M6.86 19.01h3.62v-.66c0-1.29-1.05-2.34-2.34-2.34H6.86a.86.86 0 0 0-.86.86v1.28c0 .48.39.86.86.86");
}

.mj-lwkb9n {
  fill: var(--svg-color--fff35c, #FFF35C);
  d: path("M24 22.01c0 .55.45 1 1 1h2v-3h-2c-.55 0-1 .45-1 1z");
}

.mokyx3xtu {
  stop-color: var(--svg-color--2e193b, #2E193B);
  stop-opacity: 0;
}

.ndmn59b4d {
  stop-color: var(--svg-color--59575a, #59575A);
}

.o2molzbye {
  stop-color: var(--svg-color--2e193b, #2E193B);
}

.oftc7sneh {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22 23.01a1 1 0 1 0 0-2a1 1 0 0 0 0 2Z");
}

.ongrvfd6a {
  stop-color: var(--svg-color--06a5e9, #06A5E9);
}

.ov5m9o98p {
  stop-color: var(--svg-color--f5f4f6, #F5F4F6);
  stop-opacity: 0;
}

.oyxxcxf0e {
  stop-color: var(--svg-color--c1bdc4, #C1BDC4);
}

.p6ulpsban {
  stop-color: var(--svg-color--39323d, #39323D);
}

.phlxq0fyq {
  stop-color: var(--svg-color--898889, #898889);
}

.pkb_a_bai {
  fill: var(--svg-color--9f99a1, #9F99A1);
  d: path("M19 21.01h-6c-.55 0-1 .45-1 1s.45 1 1 1h5.99c.55 0 1-.45 1-1c.01-.55-.43-1-.99-1");
}

.q026igb2j {
  d: path("M17 9.01v-2h-2v2h-3v1h8v-1z");
}

.q0ns1qj7n {
  stop-color: var(--svg-color--1bbcee, #1BBCEE);
  stop-opacity: 0;
}

.qivwlr5pk {
  stop-color: var(--svg-color--6e6e6e, #6E6E6E);
  stop-opacity: 0;
}

.qkfquqbuk {
  stop-color: var(--svg-color--89848c, #89848C);
}

.qnoj66lkr {
  stop-color: var(--svg-color--f5f4f6, #F5F4F6);
}

.qo7ff_bqw {
  stop-color: var(--svg-color--a5d7ed, #A5D7ED);
}

.qqmsgjorc {
  stop-color: var(--svg-color--ddddde, #DDDDDE);
  stop-opacity: 0;
}

.r05s05bjl {
  d: path("M24 22.01c0 .55.45 1 1 1h2v-3h-2c-.55 0-1 .45-1 1z");
}

.rjwtwdbcs {
  stop-color: var(--svg-color--898889, #898889);
  stop-opacity: 0;
}

.rml5bzb6o {
  stop-color: var(--svg-color--616972, #616972);
}

.rnewovgur {
  stop-color: var(--svg-color--d0b060, #D0B060);
}

.rnyxtsb4p {
  stop-color: var(--svg-color--ddddde, #DDDDDE);
}

.s4m5hpbxf {
  stroke: var(--svg-color--3b353e, #3B353E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8 21.01c0-.55-.436-1-.969-1H5.094v3H7.03c.533 0 .969-.45.969-1z");
}

.s86h-zbdj {
  stop-color: var(--svg-color--c8c5c8, #C8C5C8);
  stop-opacity: 0;
}

.semze1bzv {
  stop-color: var(--svg-color--666668, #666668);
  stop-opacity: 0;
}

.sn6nsmb7j {
  stop-color: var(--svg-color--a5d7ed, #A5D7ED);
  stop-opacity: 0;
}

.soczd1nzu {
  stop-color: var(--svg-color--e6e4e9, #E6E4E9);
}

.sugqmswmx {
  stop-color: var(--svg-color--a6a2aa, #A6A2AA);
}

.t2i_cg0dh {
  stop-color: var(--svg-color--7f7e7f, #7F7E7F);
  stop-opacity: 0;
}

.t2v98obvb {
  stop-color: var(--svg-color--382d3e, #382D3E);
}

.tfsvxmcqs {
  stop-color: var(--svg-color--1e85e0, #1E85E0);
}

.todd_ybti {
  stop-color: var(--svg-color--cfcdd1, #CFCDD1);
}

.tthlbdnfh {
  d: path("M22 23.01a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.uh6fg5_ca {
  stop-color: var(--svg-color--49444c, #49444C);
}

.v_xlxgp3p {
  stop-color: var(--svg-color--1e85e0, #1E85E0);
  stop-opacity: 0;
}

.v-o1r-i4x {
  stop-color: var(--svg-color--b4afb7, #B4AFB7);
}

.v0uy6qf0b {
  stop-color: var(--svg-color--252426, #252426);
  stop-opacity: 0;
}

.v2qzbu00p {
  stop-color: var(--svg-color--2c6daf, #2C6DAF);
}

.vggt17bvc {
  d: path("M13 7.01c-.55 0-1 .45-1 1v1h4v-2z");
}

.vridjdb8x {
  stop-color: var(--svg-color--ff708f, #FF708F);
  stop-opacity: 0;
}

.vwi6usgxw {
  d: path("M21.04 20.01H10.96c-.59 0-1.13-.33-1.39-.86L9 18.01h14l-.57 1.14c-.26.53-.8.86-1.39.86");
}

.w7642ybaq {
  d: path("M8 21.01c0-.55-.45-1-1-1H5v3h2c.55 0 1-.45 1-1z");
}

.wrovydbnd {
  stop-color: var(--svg-color--ff4474, #FF4474);
}

.wvqs8wszw {
  stop-color: var(--svg-color--e7c04b, #E7C04B);
}

.wwykkk7vx {
  stop-color: var(--svg-color--ece0f3, #ECE0F3);
}

.xc4v0fmgz {
  stop-color: var(--svg-color--cbcbd0, #CBCBD0);
}

.xyb04qkou {
  d: path("M25 29.01h-2c-.55 0-1-.45-1-1v-3h4v3c0 .56-.44 1-1 1");
}

.yhbaaxbfb {
  stop-color: var(--svg-color--716875, #716875);
}

.yqv10n6gc {
  stop-color: var(--svg-color--ff708f, #FF708F);
}

.z4hq-cbry {
  stop-color: var(--svg-color--e4bf50, #E4BF50);
}

.zekaiwv8e {
  stop-color: var(--svg-color--6e6e6e, #6E6E6E);
}

.zf7g7gb1d {
  stop-color: var(--svg-color--ac0650, #AC0650);
}

.zkq5yhpha {
  stop-color: var(--svg-color--d0b060, #D0B060);
  stop-opacity: 0;
}

.znpxxobat {
  stop-color: var(--svg-color--2b78c6, #2B78C6);
}

.zykhhrb2i {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10 23.01a1 1 0 1 0 0-2a1 1 0 0 0 0 2Z");
}

</style>
