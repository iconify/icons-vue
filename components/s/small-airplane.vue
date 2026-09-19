<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iTxWoPz)" transform="rotate(135 28.375 9.283)" class="y4wqn5b0t"/><rect fill="url(#i2uyqKd)" transform="rotate(45 25.192 5.497)" class="iefmv9box"/><g filter="url(#ipL3sic)"><path fill="url(#i3iAZPe)" class="f-8kvlb1v"/><path fill="url(#iRG3iKb)" class="f-8kvlb1v"/></g><path fill="url(#iGo35fc)" class="kn-z10bou"/><path fill="url(#inRq7Cd)" class="kn-z10bou"/><path fill="url(#iHMwhKC)" class="kn-z10bou"/><path fill="url(#iUhbPee)" class="kn-z10bou"/><g filter="url(#iva9WAc)"><path class="gs-566usc"/></g><path clip-rule="evenodd" class="l7z3_2sak"/><path fill="url(#iWgLKjc)" clip-rule="evenodd" class="czla-nbgj"/><path clip-rule="evenodd" class="vzsfjj72l"/><path fill="url(#iLOuWgd)" clip-rule="evenodd" class="hi8t-3b0l"/><g filter="url(#ilP4soe)"><path fill="url(#iIiYEUd)" class="xk3i0ya7k"/><path fill="url(#ibapupc)" class="xk3i0ya7k"/></g><g filter="url(#i1RUO3d)"><path fill="url(#ifMXx8c)" class="dbyruhbhy"/></g><defs><linearGradient id="iTxWoPz" x1="28.121" x2="29.821" y1="13.113" y2="13.113" gradientUnits="userSpaceOnUse"><stop class="qea17-0dv"/><stop offset="1" class="k9pclpj6v"/></linearGradient><linearGradient id="i2uyqKd" x1="26.081" x2="26.081" y1="5.497" y2="7.497" gradientUnits="userSpaceOnUse"><stop class="f9iiwtbzs"/><stop offset="1" class="unhl4jb9f"/></linearGradient><linearGradient id="i3iAZPe" x1="20.785" x2="17.223" y1="12.404" y2="16.154" gradientUnits="userSpaceOnUse"><stop class="o3t4gbcea"/><stop offset="1" class="xpd9wl9ul"/></linearGradient><linearGradient id="iGo35fc" x1="24.535" x2="9.848" y1="7.404" y2="22.216" gradientUnits="userSpaceOnUse"><stop class="gs-to5pyv"/><stop offset=".639" class="wd606n22r"/></linearGradient><linearGradient id="inRq7Cd" x1="24.723" x2="21.848" y1="7.279" y2="9.966" gradientUnits="userSpaceOnUse"><stop class="rr1et5bfi"/><stop offset="1" class="ei81miblj"/></linearGradient><linearGradient id="iHMwhKC" x1="17.068" x2="16.38" y1="18.908" y2="17.877" gradientUnits="userSpaceOnUse"><stop class="lgslczb4h"/><stop offset="1" class="fyuh_ac4y"/></linearGradient><linearGradient id="iUhbPee" x1="10.948" x2="12.326" y1="17.006" y2="18.144" gradientUnits="userSpaceOnUse"><stop class="bmkj88byq"/><stop offset="1" class="paaq_lbrg"/></linearGradient><linearGradient id="iWgLKjc" x1="20.973" x2="21.395" y1="22.341" y2="21.654" gradientUnits="userSpaceOnUse"><stop class="fd15p_bqe"/><stop offset="1" class="mkm6e_b4u"/></linearGradient><linearGradient id="iLOuWgd" x1="9.238" x2="9.9" y1="10.517" y2="10.105" gradientUnits="userSpaceOnUse"><stop class="diedwcc6w"/><stop offset="1" class="w0j5bxbif"/></linearGradient><linearGradient id="iIiYEUd" x1="9.223" x2="6.66" y1="22.716" y2="25.341" gradientUnits="userSpaceOnUse"><stop class="j90xoss9b"/><stop offset="1" class="kme-x4bjc"/></linearGradient><linearGradient id="ifMXx8c" x1="5.517" x2="10.493" y1="26.48" y2="21.478" gradientUnits="userSpaceOnUse"><stop offset=".641" class="uj7qc_j7m"/><stop offset=".695" class="h5l-zqb7r"/></linearGradient><filter id="ipL3sic" width="23.327" height="23.241" x="6.674" y="2.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.12549 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12548"/></filter><filter id="iva9WAc" width="3.986" height="3.988" x="20.452" y="7.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.54902 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12548"/></filter><filter id="ilP4soe" width="10.408" height="10.39" x="2.099" y="19.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.184314 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12548"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.403922 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12548" result="effect2_innerShadow_18_12548"/></filter><filter id="i1RUO3d" width="5.075" height="5.102" x="5.517" y="21.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.458824 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12548"/></filter><radialGradient id="iRG3iKb" cx="0" cy="0" r="1" gradientTransform="rotate(135 7.055 10.141)scale(9.40036 3.36916)" gradientUnits="userSpaceOnUse"><stop offset=".507" class="xj1iy2bcu"/><stop offset="1" class="tnf63lbrv"/></radialGradient><radialGradient id="ibapupc" cx="0" cy="0" r="1" gradientTransform="rotate(136.239 .106 13.28)scale(5.0735 1.06253)" gradientUnits="userSpaceOnUse"><stop offset=".312" class="mnl4ye3lb"/><stop offset="1" class="na23azbxz"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:small-airplane" /></template>
<style>
.bmkj88byq {
  stop-color: var(--svg-color--bdb8bb, #BDB8BB);
}

.czla-nbgj {
  fill-rule: evenodd;
  d: path("m23.847 24.03l.878-.879a.6.6 0 0 0 0-.849l-3.542-3.541a.6.6 0 0 0-.848 0l-1.961 1.96z");
}

.dbyruhbhy {
  d: path("m5.632 25.739l4.058-4.141a.4.4 0 0 1 .552-.019l.117.105a.4.4 0 0 1 .016.582l-4.11 4.097a.4.4 0 0 1-.559.007l-.064-.062a.4.4 0 0 1-.01-.57");
}

.diedwcc6w {
  stop-color: var(--svg-color--c2b8cb, #C2B8CB);
}

.ei81miblj {
  stop-color: var(--svg-color--fefefe, #FEFEFE);
  stop-opacity: 0;
}

.f-8kvlb1v {
  d: path("M29.407 21.34L10.65 2.64a.99.99 0 0 0-1.41.005c-.753.766-1.634 1.677-2.23 2.295a1.14 1.14 0 0 0-.184 1.372c1.232 2.143 4.77 8.007 6.835 11.56l11.974 7.237a1.25 1.25 0 0 0 1.515-.17l2.247-2.171a1 1 0 0 0 .011-1.428");
}

.f9iiwtbzs {
  stop-color: var(--svg-color--644a79, #644A79);
}

.fd15p_bqe {
  stop-color: var(--svg-color--c8ade1, #C8ADE1);
}

.ft5dv1b6b {
  fill: none;
}

.fyuh_ac4y {
  stop-color: var(--svg-color--e0c6f5, #E0C6F5);
  stop-opacity: 0;
}

.gs-566usc {
  fill: var(--svg-color--4ee0ff, #4EE0FF);
  d: path("m23.035 10.795l-1.826-1.928c-.335-.353-.373-.936.074-1.127c.678-.289 1.481-.094 1.815.21l.922.938c.533.533.484 1.234.25 1.804c-.21.51-.855.504-1.235.102");
}

.gs-to5pyv {
  stop-color: var(--svg-color--b5b1b7, #B5B1B7);
}

.h5l-zqb7r {
  stop-color: var(--svg-color--bdbbbd, #BDBBBD);
}

.hi8t-3b0l {
  fill-rule: evenodd;
  d: path("m11.214 13.721l2.027-2.027a.6.6 0 0 0 0-.848L9.699 7.304a.6.6 0 0 0-.849 0l-.91.91c.54.913 1.18 1.988 1.853 3.118c.465.782.946 1.59 1.42 2.39");
}

.iefmv9box {
  width: 1.779px;
  height: 4px;
  x: 25.192px;
  y: 5.497px;
  rx: 0.889px;
}

.j90xoss9b {
  stop-color: var(--svg-color--d9447b, #D9447B);
}

.k9pclpj6v {
  stop-color: var(--svg-color--342d38, #342D38);
}

.kme-x4bjc {
  stop-color: var(--svg-color--df3f53, #DF3F53);
}

.kn-z10bou {
  d: path("M19.44 7.479L6.41 24.31l1 1.469l17.151-13.144a3.25 3.25 0 0 0 .346-4.853l-.575-.587a3.25 3.25 0 0 0-4.893.284");
}

.l7z3_2sak {
  fill: var(--svg-color--f0eaf6, #F0EAF6);
  fill-rule: evenodd;
  d: path("m23.847 24.03l.878-.879a.6.6 0 0 0 0-.849l-3.542-3.541a.6.6 0 0 0-.848 0l-1.961 1.96z");
}

.lgslczb4h {
  stop-color: var(--svg-color--e0c6f5, #E0C6F5);
}

.mkm6e_b4u {
  stop-color: var(--svg-color--c8ade1, #C8ADE1);
  stop-opacity: 0;
}

.mnl4ye3lb {
  stop-color: var(--svg-color--b43a5f, #B43A5F);
}

.na23azbxz {
  stop-color: var(--svg-color--b43a5f, #B43A5F);
  stop-opacity: 0;
}

.o3t4gbcea {
  stop-color: var(--svg-color--f86891, #F86891);
}

.paaq_lbrg {
  stop-color: var(--svg-color--bdb8bb, #BDB8BB);
  stop-opacity: 0;
}

.qea17-0dv {
  stop-color: var(--svg-color--4f3962, #4F3962);
}

.rr1et5bfi {
  stop-color: var(--svg-color--fefefe, #FEFEFE);
}

.tnf63lbrv {
  stop-color: var(--svg-color--bc4756, #BC4756);
  stop-opacity: 0;
}

.uj7qc_j7m {
  stop-color: var(--svg-color--98929f, #98929F);
}

.unhl4jb9f {
  stop-color: var(--svg-color--090909, #090909);
}

.vzsfjj72l {
  fill: var(--svg-color--f0eaf6, #F0EAF6);
  fill-rule: evenodd;
  d: path("m11.214 13.721l2.027-2.027a.6.6 0 0 0 0-.848L9.699 7.304a.6.6 0 0 0-.849 0l-.91.91c.54.913 1.18 1.988 1.853 3.118c.465.782.946 1.59 1.42 2.39");
}

.w0j5bxbif {
  stop-color: var(--svg-color--c2b8cb, #C2B8CB);
  stop-opacity: 0;
}

.wd606n22r {
  stop-color: var(--svg-color--f0e3f6, #F0E3F6);
}

.xj1iy2bcu {
  stop-color: var(--svg-color--bc4756, #BC4756);
}

.xk3i0ya7k {
  d: path("m10.368 29.535l-7.952-7.923a.4.4 0 0 1 .004-.57l1.3-1.267a.4.4 0 0 1 .485-.057l5.023 3.008a.4.4 0 0 1 .14.142l2.884 4.982a.4.4 0 0 1-.07.49l-1.255 1.2a.4.4 0 0 1-.56-.005");
}

.xpd9wl9ul {
  stop-color: var(--svg-color--eb4152, #EB4152);
}

.y4wqn5b0t {
  width: 1.18px;
  height: 7.977px;
  x: 28.375px;
  y: 9.283px;
  rx: 0.59px;
}

</style>
