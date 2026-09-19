<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iCedw0b)" class="u5j4yd01d"/><rect fill="url(#iErxoHV)" class="u5j4yd01d"/><g filter="url(#ifH5nKb)"><path class="e54t6jl0h"/><path fill="url(#iaUvD0c)" class="ym9i-k-vc"/></g><g filter="url(#i5AEPhd)"><path class="jtn9rybxi"/></g><g filter="url(#i8EFqFc)"><path class="x2uko1b3s"/></g><g filter="url(#ihuBQ4c)"><path class="idxn86t4x"/></g><g filter="url(#imTGLXZ)"><path class="a9u37qyfq"/><path fill="url(#ibYwNUc)" class="isxow8bkf"/></g><g filter="url(#ior1eHd)"><path class="wkrwfyoot"/></g><g filter="url(#ipkfxfd)"><path class="ixbiunasm"/></g><g filter="url(#i8dqe3c)"><path class="bx6ukzblk"/><path fill="url(#iycHt9L)" class="hr9-3ubko"/></g><g filter="url(#ih0Rdwc)"><path class="og9advbwv"/></g><g filter="url(#iSDXtcb)"><path fill="url(#igMwcLd)" class="n4e1e31xb"/></g><g filter="url(#i16v3jt)"><path fill="url(#i9JYYkc)" class="kiv79-z0p"/><path fill="url(#iSEAOle)" class="kiv79-z0p"/><path fill="url(#iUSyQEb)" class="kiv79-z0p"/><path fill="url(#iBrzOgd)" class="kiv79-z0p"/><path fill="url(#ihwD5yc)" class="kiv79-z0p"/></g><path fill="url(#iIBmJdb)" class="dczocimlt"/><path fill="url(#iEYEohe)" class="dczocimlt"/><path fill="url(#iQOtyKc)" class="dczocimlt"/><path fill="url(#iOE2Xse)" class="dczocimlt"/><g filter="url(#iGekNGc)"><path fill="url(#iavfC6c)" class="k1i2txbqm"/><path fill="url(#ibJpq9k)" class="k1i2txbqm"/><path fill="url(#iRHMJpe)" class="k1i2txbqm"/></g><defs><linearGradient id="iCedw0b" x1="20.031" x2="20.031" y1="7.986" y2="26.447" gradientUnits="userSpaceOnUse"><stop class="mxpm9wbyq"/><stop offset="1" class="ybphyjb-s"/></linearGradient><linearGradient id="iErxoHV" x1="10.117" x2="12.417" y1="22.282" y2="22.344" gradientUnits="userSpaceOnUse"><stop offset=".031" class="veun7cb3s"/><stop offset="1" class="idv7f0bli"/></linearGradient><linearGradient id="iaUvD0c" x1="13.427" x2="14.468" y1="11.482" y2="11.482" gradientUnits="userSpaceOnUse"><stop offset=".333" class="h_fr6gbhe"/><stop offset="1" class="nn3wdhnkh"/></linearGradient><linearGradient id="ibYwNUc" x1="13.427" x2="14.468" y1="23.137" y2="23.137" gradientUnits="userSpaceOnUse"><stop offset=".333" class="h_fr6gbhe"/><stop offset="1" class="nn3wdhnkh"/></linearGradient><linearGradient id="iycHt9L" x1="23.652" x2="24.693" y1="17.31" y2="17.31" gradientUnits="userSpaceOnUse"><stop offset=".333" class="h_fr6gbhe"/><stop offset="1" class="nn3wdhnkh"/></linearGradient><linearGradient id="igMwcLd" x1="28.438" x2="28.438" y1="6.152" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="rm61x3idb"/><stop offset="1" class="rfn3a3l7h"/></linearGradient><linearGradient id="i9JYYkc" x1="20.031" x2="20.031" y1="2.609" y2="6.712" gradientUnits="userSpaceOnUse"><stop class="z613fsbfq"/><stop offset="1" class="b462nc3ap"/></linearGradient><linearGradient id="iSEAOle" x1="21.181" x2="21.181" y1="6.867" y2="6.183" gradientUnits="userSpaceOnUse"><stop class="i0k5pcbic"/><stop offset="1" class="ke7h_0nog"/></linearGradient><linearGradient id="iUSyQEb" x1="10.117" x2="13.318" y1="6.712" y2="6.712" gradientUnits="userSpaceOnUse"><stop offset=".136" class="zhmf_hb6m"/><stop offset="1" class="dtkgx-g_z"/></linearGradient><linearGradient id="iBrzOgd" x1="29.945" x2="27.024" y1="6.712" y2="6.712" gradientUnits="userSpaceOnUse"><stop offset=".128" class="u6z2bmfhr"/><stop offset="1" class="bxwl5sscl"/></linearGradient><linearGradient id="iIBmJdb" x1="20.031" x2="20.031" y1="26.323" y2="30.378" gradientUnits="userSpaceOnUse"><stop class="zf56z5fxh"/><stop offset="1" class="jhar9mbzr"/></linearGradient><linearGradient id="iEYEohe" x1="10.117" x2="12.51" y1="27.566" y2="27.566" gradientUnits="userSpaceOnUse"><stop offset=".164" class="zfjq88vrv"/><stop offset="1" class="n866a4bbg"/></linearGradient><linearGradient id="iOE2Xse" x1="19.72" x2="19.72" y1="26.043" y2="26.633" gradientUnits="userSpaceOnUse"><stop offset=".158" class="o-u9ei9cl"/><stop offset="1" class="p7igwxbie"/></linearGradient><linearGradient id="iavfC6c" x1="11.75" x2="2.094" y1="16.484" y2="16.484" gradientUnits="userSpaceOnUse"><stop class="saflp77kz"/><stop offset="1" class="c57k0eroi"/></linearGradient><linearGradient id="ibJpq9k" x1="10.094" x2="9.344" y1="13.766" y2="14.547" gradientUnits="userSpaceOnUse"><stop offset=".261" class="wiuu72ckh"/><stop offset="1" class="wxrevestz"/></linearGradient><linearGradient id="iRHMJpe" x1="9.406" x2="9.063" y1="19.109" y2="18.75" gradientUnits="userSpaceOnUse"><stop class="d86t6_bcf"/><stop offset="1" class="y__zv5jlg"/></linearGradient><filter id="ifH5nKb" width="3.894" height="3.894" x="12.972" y="8.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.384314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.498039 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="i5AEPhd" width="3.894" height="3.894" x="18.084" y="8.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.572549 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.709804 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="i8EFqFc" width="3.894" height="3.894" x="23.197" y="8.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.752941 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.858824 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="ihuBQ4c" width="3.894" height="3.894" x="12.972" y="14.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.572549 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.709804 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="imTGLXZ" width="3.894" height="3.894" x="12.972" y="20.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.384314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.498039 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="ior1eHd" width="3.894" height="3.894" x="18.084" y="14.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.752941 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.858824 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="ipkfxfd" width="3.894" height="3.894" x="18.084" y="20.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.572549 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.709804 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="i8dqe3c" width="3.894" height="3.894" x="23.197" y="14.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.384314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.498039 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="ih0Rdwc" width="3.894" height="3.894" x="23.197" y="20.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.752941 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.858824 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19091" result="effect2_innerShadow_18_19091"/></filter><filter id="iSDXtcb" width="3.523" height="23.724" x="26.677" y="5.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19091" stdDeviation=".5"/></filter><filter id="i16v3jt" width="19.828" height="4.202" x="10.117" y="2.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.407843 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/></filter><filter id="iGekNGc" width="10.455" height="10.736" x="2.094" y="10.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.568627 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19091"/></filter><radialGradient id="ihwD5yc" cx="0" cy="0" r="1" gradientTransform="matrix(-.65265 0 0 -3.1545 29.945 6.432)" gradientUnits="userSpaceOnUse"><stop class="ojzy8gu1i"/><stop offset="1" class="tg-jatb9a"/></radialGradient><radialGradient id="iQOtyKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.0768 -1.6161 0 28.298 25.98)" gradientUnits="userSpaceOnUse"><stop class="pil3f0bpq"/><stop offset="1" class="iukqjcxpk"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mobile-phone-with-arrow" /></template>
<style>
.a9u37qyfq {
  fill: var(--svg-color--ff9544, #FF9544);
  d: path("M13.272 21.27c0-.329.267-.596.596-.596h2.101c.33 0 .597.267.597.596v2.102a.596.596 0 0 1-.597.596h-2.1a.597.597 0 0 1-.597-.596z");
}

.b462nc3ap {
  stop-color: var(--svg-color--6c6ebe, #6C6EBE);
}

.bx6ukzblk {
  fill: var(--svg-color--ff9544, #FF9544);
  d: path("M23.497 15.443c0-.33.267-.596.596-.596h2.101c.33 0 .597.267.597.596v2.101c0 .33-.267.597-.597.597h-2.1a.597.597 0 0 1-.597-.597z");
}

.bxwl5sscl {
  stop-color: var(--svg-color--7277c8, #7277C8);
  stop-opacity: 0;
}

.c57k0eroi {
  stop-color: var(--svg-color--38b5ff, #38B5FF);
}

.d86t6_bcf {
  stop-color: var(--svg-color--2aacfa, #2AACFA);
}

.dczocimlt {
  d: path("M29.945 26.323v1.47a2.586 2.586 0 0 1-2.585 2.585H12.703a2.586 2.586 0 0 1-2.586-2.585v-1.47z");
}

.dtkgx-g_z {
  stop-color: var(--svg-color--5e61ad, #5E61AD);
  stop-opacity: 0;
}

.e54t6jl0h {
  fill: var(--svg-color--ff9544, #FF9544);
  d: path("M13.272 9.616c0-.33.267-.597.596-.597h2.101c.33 0 .597.267.597.597v2.1c0 .33-.267.598-.597.598h-2.1a.597.597 0 0 1-.597-.597z");
}

.ft5dv1b6b {
  fill: none;
}

.h_fr6gbhe {
  stop-color: var(--svg-color--ff945c, #FF945C);
}

.hr9-3ubko {
  d: path("M23.497 15.443c0-.33.267-.596.596-.596h2.101c.33 0 .597.267.597.596v2.101c0 .33-.267.597-.597.597h-2.1a.597.597 0 0 1-.597-.597z");
}

.i0k5pcbic {
  stop-color: var(--svg-color--6062b1, #6062B1);
}

.idv7f0bli {
  stop-color: var(--svg-color--412c4c, #412C4C);
  stop-opacity: 0;
}

.idxn86t4x {
  fill: var(--svg-color--38c6ff, #38C6FF);
  d: path("M13.272 15.443c0-.33.267-.596.596-.596h2.101c.33 0 .597.267.597.596v2.101c0 .33-.267.597-.597.597h-2.1a.597.597 0 0 1-.597-.597z");
}

.isxow8bkf {
  d: path("M13.272 21.27c0-.329.267-.596.596-.596h2.101c.33 0 .597.267.597.596v2.102a.596.596 0 0 1-.597.596h-2.1a.597.597 0 0 1-.597-.596z");
}

.iukqjcxpk {
  stop-color: var(--svg-color--6b5094, #6B5094);
  stop-opacity: 0;
}

.ixbiunasm {
  fill: var(--svg-color--38c6ff, #38C6FF);
  d: path("M18.384 21.27c0-.329.267-.596.597-.596h2.1c.33 0 .597.267.597.596v2.102a.596.596 0 0 1-.596.596H18.98a.597.597 0 0 1-.597-.596z");
}

.jhar9mbzr {
  stop-color: var(--svg-color--76509e, #76509E);
}

.jtn9rybxi {
  fill: var(--svg-color--38c6ff, #38C6FF);
  d: path("M18.384 9.616c0-.33.267-.597.597-.597h2.1c.33 0 .597.267.597.597v2.1c0 .33-.267.598-.596.598H18.98a.597.597 0 0 1-.597-.597z");
}

.k1i2txbqm {
  d: path("M7.049 10.888a.6.6 0 0 0-1.002.445v2.16a.5.5 0 0 1-.5.5H3.094a1 1 0 0 0-1 1v2.077a1 1 0 0 0 1 1h2.453a.5.5 0 0 1 .5.5v2.097a.6.6 0 0 0 1.002.445l5.052-4.555a.75.75 0 0 0 0-1.114z");
}

.ke7h_0nog {
  stop-color: var(--svg-color--6062b1, #6062B1);
  stop-opacity: 0;
}

.kiv79-z0p {
  d: path("M29.945 6.712H10.117V5.195a2.586 2.586 0 0 1 2.586-2.586H27.36a2.586 2.586 0 0 1 2.585 2.586z");
}

.mxpm9wbyq {
  stop-color: var(--svg-color--62326d, #62326D);
}

.n4e1e31xb {
  d: path("M27.677 6.152H29.2v21.724h-1.523z");
}

.n866a4bbg {
  stop-color: var(--svg-color--6e4693, #6E4693);
  stop-opacity: 0;
}

.nn3wdhnkh {
  stop-color: var(--svg-color--ff945c, #FF945C);
  stop-opacity: 0;
}

.o-u9ei9cl {
  stop-color: var(--svg-color--5e3d7f, #5E3D7F);
}

.og9advbwv {
  fill: var(--svg-color--ffec58, #FFEC58);
  d: path("M23.497 21.27c0-.329.267-.596.596-.596h2.101c.33 0 .597.267.597.596v2.102a.596.596 0 0 1-.597.596h-2.1a.597.597 0 0 1-.597-.596z");
}

.ojzy8gu1i {
  stop-color: var(--svg-color--6c6fb4, #6C6FB4);
}

.p7igwxbie {
  stop-color: var(--svg-color--5e3d7f, #5E3D7F);
  stop-opacity: 0;
}

.pil3f0bpq {
  stop-color: var(--svg-color--6b5094, #6B5094);
}

.rfn3a3l7h {
  stop-color: var(--svg-color--555187, #555187);
}

.rm61x3idb {
  stop-color: var(--svg-color--674876, #674876);
}

.saflp77kz {
  stop-color: var(--svg-color--44c0ff, #44C0FF);
}

.tg-jatb9a {
  stop-color: var(--svg-color--6c6fb4, #6C6FB4);
  stop-opacity: 0;
}

.u5j4yd01d {
  width: 19.828px;
  height: 27.769px;
  x: 10.117px;
  y: 2.609px;
  rx: 2.6px;
}

.u6z2bmfhr {
  stop-color: var(--svg-color--7277c8, #7277C8);
}

.veun7cb3s {
  stop-color: var(--svg-color--412c4c, #412C4C);
}

.wiuu72ckh {
  stop-color: var(--svg-color--49c4ff, #49C4FF);
}

.wkrwfyoot {
  fill: var(--svg-color--ffec58, #FFEC58);
  d: path("M18.384 15.443c0-.33.267-.596.597-.596h2.1c.33 0 .597.267.597.596v2.101c0 .33-.267.597-.596.597H18.98a.597.597 0 0 1-.597-.597z");
}

.wxrevestz {
  stop-color: var(--svg-color--49c4ff, #49C4FF);
  stop-opacity: 0;
}

.x2uko1b3s {
  fill: var(--svg-color--ffec58, #FFEC58);
  d: path("M23.497 9.616c0-.33.267-.597.596-.597h2.101c.33 0 .597.267.597.597v2.1c0 .33-.267.598-.597.598h-2.1a.597.597 0 0 1-.597-.597z");
}

.y__zv5jlg {
  stop-color: var(--svg-color--2aacfa, #2AACFA);
  stop-opacity: 0;
}

.ybphyjb-s {
  stop-color: var(--svg-color--434486, #434486);
}

.ym9i-k-vc {
  d: path("M13.272 9.616c0-.33.267-.597.596-.597h2.101c.33 0 .597.267.597.597v2.1c0 .33-.267.598-.597.598h-2.1a.597.597 0 0 1-.597-.597z");
}

.z613fsbfq {
  stop-color: var(--svg-color--636ab6, #636AB6);
}

.zf56z5fxh {
  stop-color: var(--svg-color--6b4390, #6B4390);
}

.zfjq88vrv {
  stop-color: var(--svg-color--4f3d6c, #4F3D6C);
}

.zhmf_hb6m {
  stop-color: var(--svg-color--484b86, #484B86);
}

</style>
