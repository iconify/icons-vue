<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKIXCBc)"><path fill="url(#iwfTHCb)" class="tatlmonxk"/></g><path fill="url(#it7Ubwc)" class="tatlmonxk"/><path fill="url(#iFQWamc)" class="mwub_zbcl"/><path fill="url(#iuszYAe)" class="mwub_zbcl"/><path fill="url(#isHNpAb)" class="mwub_zbcl"/><path fill="url(#ieqyaDj)" class="mwub_zbcl"/><path fill="url(#it7Ubwc)" class="tatlmonxk"/><g filter="url(#iFdkg2s)"><path class="nxnn_qemd"/></g><g filter="url(#iNNsVlb)"><path class="nlcn3nb0v"/></g><path class="fkwh56dfm"/><path fill="url(#irxXdae)" class="u8-hrbcqx"/><path fill="url(#i0Chnwb)" class="u8-hrbcqx"/><path fill="url(#ixJz5zj)" class="u8-hrbcqx"/><path fill="url(#i0LfQxe)" class="u8-hrbcqx"/><g filter="url(#iQkNt2b)"><path class="gru5x2otu"/></g><g filter="url(#iQcJyZb)"><path class="vz597ubci"/></g><path fill="url(#ilusNHd)" class="onbn4ccoa"/><path fill="url(#iA7n9se)" class="nbqe6bcov"/><path fill="url(#iYITX3b)" class="nbqe6bcov"/><path fill="url(#iWq7e3d)" class="y8rleobni"/><path fill="url(#i68FYyc)" class="y8rleobni"/><g filter="url(#ikhSXye)"><path class="moed3rbdf"/></g><rect fill="url(#iJ4Xpsd)" class="m6vl8b49j"/><g filter="url(#i4u09Yb)"><rect class="wbqj065kl"/><rect fill="url(#iLH6jJb)" class="m6vl8b49j"/></g><g filter="url(#iiDjbme)"><rect class="f5br6dxdm"/><rect fill="url(#ic1T3kQ)" class="nuo-ykban"/></g><g filter="url(#idgJ7nW)"><rect transform="rotate(25.727 14.569 16.547)" class="crkhtacmp"/><rect fill="url(#iOGTZHy)" transform="rotate(25.727 14.569 16.547)" class="u1k5uvb0p"/><rect fill="url(#iSdzftd)" transform="rotate(25.727 14.569 16.547)" class="u1k5uvb0p"/><rect fill="url(#i3Axolb)" transform="rotate(25.727 14.569 16.547)" class="u1k5uvb0p"/></g><g filter="url(#iItsXrc)"><rect transform="scale(-1 1)rotate(25.727 -44.796 -29.236)" class="oi8rr6bpr"/><rect fill="url(#i93muGb)" transform="scale(-1 1)rotate(25.727 -44.796 -29.236)" class="jeb2f8ekc"/></g><g filter="url(#i8S6hCb)"><path class="m4z1kxb-u"/><path fill="url(#il5BRLe)" class="q18_l0bkd"/></g><defs><linearGradient id="iwfTHCb" x1="25.012" x2="8.504" y1="9.159" y2="23.811" gradientUnits="userSpaceOnUse"><stop class="shui8yufi"/><stop offset="0" class="f71to4bsz"/><stop offset="1" class="dyj78c40b"/></linearGradient><linearGradient id="it7Ubwc" x1="15.832" x2="15.832" y1="27.074" y2="26.427" gradientUnits="userSpaceOnUse"><stop class="wstbsmd-b"/><stop offset="1" class="x7hmozbub"/></linearGradient><linearGradient id="iFQWamc" x1="7.29" x2="10.226" y1="21.561" y2="21.474" gradientUnits="userSpaceOnUse"><stop class="htg3rzwjq"/><stop offset="1" class="qc47m5egv"/></linearGradient><linearGradient id="iuszYAe" x1="23.852" x2="21.352" y1="19.423" y2="19.423" gradientUnits="userSpaceOnUse"><stop class="byyyribhu"/><stop offset="1" class="kkovdc-kj"/></linearGradient><linearGradient id="irxXdae" x1="15.837" x2="15.837" y1="5.719" y2="11.094" gradientUnits="userSpaceOnUse"><stop class="sj17edbza"/><stop offset="1" class="jchiakbjm"/></linearGradient><linearGradient id="i0Chnwb" x1="17.837" x2="16.977" y1="9.688" y2="9.328" gradientUnits="userSpaceOnUse"><stop class="xlx-yobfx"/><stop offset="1" class="k2d5zcb_w"/></linearGradient><linearGradient id="i0LfQxe" x1="15.837" x2="15.837" y1="13.906" y2="11.719" gradientUnits="userSpaceOnUse"><stop class="x9gflt2ma"/><stop offset="1" class="azazhnbti"/></linearGradient><linearGradient id="ilusNHd" x1="15.462" x2="14.993" y1="14.531" y2="14.313" gradientUnits="userSpaceOnUse"><stop offset=".016" class="xf2nv968r"/><stop offset="1" class="wu-lipbol"/></linearGradient><linearGradient id="iA7n9se" x1="4.009" x2="4.384" y1="19.453" y2="18.813" gradientUnits="userSpaceOnUse"><stop class="qsco87qdf"/><stop offset="1" class="k6phhdcga"/></linearGradient><linearGradient id="iWq7e3d" x1="22.602" x2="25.915" y1="20.637" y2="16.625" gradientUnits="userSpaceOnUse"><stop class="veac-2t6v"/><stop offset="1" class="pox28mekv"/></linearGradient><linearGradient id="i68FYyc" x1="27.655" x2="27.28" y1="19.453" y2="18.813" gradientUnits="userSpaceOnUse"><stop class="qsco87qdf"/><stop offset="1" class="k6phhdcga"/></linearGradient><linearGradient id="iJ4Xpsd" x1="9.063" x2="15.052" y1="17.469" y2="17.469" gradientUnits="userSpaceOnUse"><stop class="te2f2gn1z"/><stop offset="1" class="ydokdebep"/></linearGradient><linearGradient id="iLH6jJb" x1="14.771" x2="11.95" y1="17.526" y2="17.526" gradientUnits="userSpaceOnUse"><stop class="ix19xlbvs"/><stop offset="1" class="ydxev5bir"/></linearGradient><linearGradient id="iOGTZHy" x1="16.219" x2="15.62" y1="20.106" y2="20.087" gradientUnits="userSpaceOnUse"><stop class="uoheajbde"/><stop offset="1" class="qfkrncbpa"/></linearGradient><linearGradient id="iSdzftd" x1="16.558" x2="15.89" y1="18.978" y2="19.067" gradientUnits="userSpaceOnUse"><stop class="t-my5absn"/><stop offset="1" class="l4iitbbve"/></linearGradient><linearGradient id="i93muGb" x1="-.066" x2=".535" y1="2.484" y2="2.469" gradientUnits="userSpaceOnUse"><stop offset=".085" class="v-haecc_w"/><stop offset="1" class="zvlci6bkz"/></linearGradient><filter id="iKIXCBc" width="29.001" height="21.52" x="1.332" y="5.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.764706 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2663"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.933333 0 0 0 0 0.960784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2663" result="effect2_innerShadow_18_2663"/></filter><filter id="iFdkg2s" width="7.395" height="11.391" x="13.479" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2663" stdDeviation=".25"/></filter><filter id="iNNsVlb" width="6.416" height="11.002" x="10.084" y="5.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2663" stdDeviation=".25"/></filter><filter id="iQkNt2b" width="7.323" height="11.546" x="14.101" y="5.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.537255 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2663"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.737255 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2663" result="effect2_innerShadow_18_2663"/></filter><filter id="iQcJyZb" width="5.716" height="10.302" x="10.251" y="5.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.537255 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2663"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.737255 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2663" result="effect2_innerShadow_18_2663"/></filter><filter id="ikhSXye" width="16.422" height="7.29" x="7.489" y="16.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2663" stdDeviation=".5"/></filter><filter id="i4u09Yb" width="7.663" height="1.877" x="8.337" y="16.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.317647 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2663"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.192157 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2663" result="effect2_innerShadow_18_2663"/></filter><filter id="iiDjbme" width="7.663" height="1.877" x="15.664" y="16.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.376471 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2663"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.25098 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2663" result="effect2_innerShadow_18_2663"/></filter><filter id="idgJ7nW" width="3.76" height="5.825" x="12.224" y="16.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.231373 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2663"/></filter><filter id="iItsXrc" width="3.76" height="5.825" x="15.966" y="16.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.196078 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2663"/></filter><filter id="i8S6hCb" width="2.461" height="1.711" x="14.768" y="16.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.180392 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2663"/></filter><radialGradient id="isHNpAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 2.03125 -3.8408 3.13173 8.009 12.219)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="fk7e9jt8h"/><stop offset="1" class="g3jwhzd1e"/></radialGradient><radialGradient id="ieqyaDj" cx="0" cy="0" r="1" gradientTransform="rotate(122.229 8.284 12.56)scale(2.88146 4.18365)" gradientUnits="userSpaceOnUse"><stop class="rpgnowb4l"/><stop offset="1" class="c8v9r-8rx"/></radialGradient><radialGradient id="ixJz5zj" cx="0" cy="0" r="1" gradientTransform="rotate(154.771 9.107 4.926)scale(4.17899 2.69621)" gradientUnits="userSpaceOnUse"><stop class="hru70pbft"/><stop offset="1" class="q3qyhdc_q"/></radialGradient><radialGradient id="iYITX3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 1.875 -1.19808 -.4992 8.79 18.125)" gradientUnits="userSpaceOnUse"><stop class="mc732ibbb"/><stop offset="1" class="lyevpzb4n"/></radialGradient><radialGradient id="ic1T3kQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.70752 1.59614 -2.25351 -2.41077 23.123 15.93)" gradientUnits="userSpaceOnUse"><stop class="i477nyb0p"/><stop offset="1" class="y0w3owbag"/></radialGradient><radialGradient id="i3Axolb" cx="0" cy="0" r="1" gradientTransform="rotate(89.793 -.966 16.307)scale(5.34682 1.76229)" gradientUnits="userSpaceOnUse"><stop offset=".893" class="x7_otxb7w"/><stop offset="1" class="yw-5m9bmz"/></radialGradient><radialGradient id="il5BRLe" cx="0" cy="0" r="1" gradientTransform="rotate(105.031 2.055 14.902)scale(1.45648 1.14474)" gradientUnits="userSpaceOnUse"><stop class="ax0rvh15k"/><stop offset="1" class="i-r52bfnk"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:martial-arts-uniform" /></template>
<style>
.ax0rvh15k {
  stop-color: var(--svg-color--7c759c, #7C759C);
}

.azazhnbti {
  stop-color: var(--svg-color--2b2c57, #2B2C57);
  stop-opacity: 0;
}

.byyyribhu {
  stop-color: var(--svg-color--e0dcec, #E0DCEC);
}

.c8v9r-8rx {
  stop-color: var(--svg-color--d3cede, #D3CEDE);
  stop-opacity: 0;
}

.crkhtacmp {
  width: 1.589px;
  height: 6.014px;
  x: 14.569px;
  y: 16.547px;
  fill: var(--svg-color--564b71, #564B71);
  rx: 0.794px;
}

.dyj78c40b {
  stop-color: var(--svg-color--c9c2d7, #C9C2D7);
}

.f5br6dxdm {
  width: 7.663px;
  height: 1.477px;
  x: 15.664px;
  y: 16.508px;
  fill: var(--svg-color--605e87, #605E87);
  rx: 0.6px;
}

.f71to4bsz {
  stop-color: var(--svg-color--d4cfde, #D4CFDE);
}

.fk7e9jt8h {
  stop-color: var(--svg-color--cdc7da, #CDC7DA);
}

.fkwh56dfm {
  fill: var(--svg-color--524d75, #524D75);
  d: path("M19.445 5.952L15.85 13.68l-3.621-7.728z");
}

.ft5dv1b6b {
  fill: none;
}

.g3jwhzd1e {
  stop-color: var(--svg-color--cdc7da, #CDC7DA);
  stop-opacity: 0;
}

.gru5x2otu {
  fill: var(--svg-color--a9a3b2, #A9A3B2);
  d: path("m16.18 16.922l5.055-10.675a.4.4 0 0 0-.362-.571h-.918a.6.6 0 0 0-.543.343l-5.161 10.903z");
}

.hru70pbft {
  stop-color: var(--svg-color--5b4a6f, #5B4A6F);
}

.htg3rzwjq {
  stop-color: var(--svg-color--a9a1b6, #A9A1B6);
}

.i-r52bfnk {
  stop-color: var(--svg-color--7c759c, #7C759C);
  stop-opacity: 0;
}

.i477nyb0p {
  stop-color: var(--svg-color--7a7ba3, #7A7BA3);
}

.ix19xlbvs {
  stop-color: var(--svg-color--594f74, #594F74);
}

.jchiakbjm {
  stop-color: var(--svg-color--5f4b73, #5F4B73);
  stop-opacity: 0;
}

.jeb2f8ekc {
  width: 1.589px;
  height: 6.014px;
  rx: 0.794px;
}

.k2d5zcb_w {
  stop-color: var(--svg-color--333259, #333259);
  stop-opacity: 0;
}

.k6phhdcga {
  stop-color: var(--svg-color--9a86b1, #9A86B1);
  stop-opacity: 0;
}

.kkovdc-kj {
  stop-color: var(--svg-color--e0dcec, #E0DCEC);
  stop-opacity: 0;
}

.l4iitbbve {
  stop-color: var(--svg-color--362b5a, #362B5A);
  stop-opacity: 0;
}

.lyevpzb4n {
  stop-color: var(--svg-color--8c7aa1, #8C7AA1);
  stop-opacity: 0;
}

.m4z1kxb-u {
  fill: var(--svg-color--605584, #605584);
  d: path("m14.85 17.46l-.077-.49a.4.4 0 0 1 .396-.462h1.41a.4.4 0 0 1 .392.48l-.101.5a.6.6 0 0 1-.588.48h-.84a.6.6 0 0 1-.592-.507");
}

.m6vl8b49j {
  width: 7.663px;
  height: 1.477px;
  x: 8.337px;
  y: 16.508px;
  rx: 0.6px;
}

.mc732ibbb {
  stop-color: var(--svg-color--8c7aa1, #8C7AA1);
}

.moed3rbdf {
  fill: var(--svg-color--6e5a87, #6E5A87);
  d: path("M9.029 17.238a.54.54 0 0 0-.54.54v.112c0 .298.242.54.54.54h4.444l-1.416 3.073a.715.715 0 0 0 1.288.62l1.728-3.722l.013-.029a.5.5 0 0 0 .146-.107a.5.5 0 0 0 .187.126l.005.01l1.727 3.723a.714.714 0 1 0 1.288-.62l-1.415-3.074h5.348a.54.54 0 0 0 .54-.54v-.112a.54.54 0 0 0-.54-.54H15.62a.54.54 0 0 0-.388.165a.54.54 0 0 0-.389-.165z");
}

.mwub_zbcl {
  d: path("M8.337 26.498c0 .265.3.474.66.474h13.68c.33 0 .596-.172.65-.392V12.123a2.5 2.5 0 0 0-1.11-.248H9.447c-.404 0-.79.091-1.11.252z");
}

.nbqe6bcov {
  d: path("M8.337 6.302c-.22.16-.41.36-.56.61l-5.81 10.07c-.28.48-.11 1.1.37 1.38l3.71 2.14c.48.28 1.1.11 1.38-.37l.91-1.57z");
}

.nlcn3nb0v {
  fill: var(--svg-color--a09da7, #A09DA7);
  d: path("M16 14.136L12.448 6.55a.6.6 0 0 0-.544-.346h-.92a.4.4 0 0 0-.362.57l4.408 9.432z");
}

.nuo-ykban {
  width: 7.663px;
  height: 1.477px;
  x: 15.664px;
  y: 16.508px;
  rx: 0.6px;
}

.nxnn_qemd {
  fill: var(--svg-color--a09da7, #A09DA7);
  d: path("M15.741 16.922L20.336 7.1a.4.4 0 0 0-.362-.57h-.752a.6.6 0 0 0-.543.346l-4.7 10.045z");
}

.oi8rr6bpr {
  width: 1.589px;
  height: 6.014px;
  fill: var(--svg-color--5f5a81, #5F5A81);
  rx: 0.794px;
}

.onbn4ccoa {
  d: path("m15.817 13.612l-3.553-7.587a.6.6 0 0 0-.543-.345h-.92a.4.4 0 0 0-.362.569l4.408 9.433z");
}

.pox28mekv {
  stop-color: var(--svg-color--b8aecb, #B8AECB);
  stop-opacity: 0;
}

.q18_l0bkd {
  d: path("m14.85 17.46l-.077-.49a.4.4 0 0 1 .396-.462h1.41a.4.4 0 0 1 .392.48l-.101.5a.6.6 0 0 1-.588.48h-.84a.6.6 0 0 1-.592-.507");
}

.q3qyhdc_q {
  stop-color: var(--svg-color--5b4a6f, #5B4A6F);
  stop-opacity: 0;
}

.qc47m5egv {
  stop-color: var(--svg-color--a9a1b6, #A9A1B6);
  stop-opacity: 0;
}

.qfkrncbpa {
  stop-color: var(--svg-color--5c5376, #5C5376);
  stop-opacity: 0;
}

.qsco87qdf {
  stop-color: var(--svg-color--9a86b1, #9A86B1);
}

.rpgnowb4l {
  stop-color: var(--svg-color--d3cede, #D3CEDE);
}

.shui8yufi {
  stop-color: var(--svg-color--d4cfdf, #D4CFDF);
}

.sj17edbza {
  stop-color: var(--svg-color--5f4b73, #5F4B73);
}

.t-my5absn {
  stop-color: var(--svg-color--362b5a, #362B5A);
}

.tatlmonxk {
  d: path("m29.697 16.972l-5.81-10.06c-.34-.6-.98-.96-1.67-.96H9.447c-.69 0-1.33.37-1.67.96l-5.81 10.07c-.28.48-.11 1.1.37 1.38l3.71 2.14c.48.28 1.1.11 1.38-.37l.91-1.57v7.75c0 .37.3.66.66.66h13.68c.37 0 .66-.3.66-.66v-7.74l.9 1.56c.28.48.9.65 1.38.37l3.72-2.14c.47-.29.64-.9.36-1.39");
}

.te2f2gn1z {
  stop-color: var(--svg-color--56496e, #56496E);
}

.u1k5uvb0p {
  width: 1.589px;
  height: 6.014px;
  x: 14.569px;
  y: 16.547px;
  rx: 0.794px;
}

.u8-hrbcqx {
  d: path("M19.445 5.952L15.85 13.68l-3.621-7.728z");
}

.uoheajbde {
  stop-color: var(--svg-color--5c5376, #5C5376);
}

.v-haecc_w {
  stop-color: var(--svg-color--797497, #797497);
}

.veac-2t6v {
  stop-color: var(--svg-color--b8aecb, #B8AECB);
}

.vz597ubci {
  fill: var(--svg-color--a9a3b2, #A9A3B2);
  d: path("m15.817 13.612l-3.553-7.587a.6.6 0 0 0-.543-.345h-.92a.4.4 0 0 0-.362.569l4.408 9.433z");
}

.wbqj065kl {
  width: 7.663px;
  height: 1.477px;
  x: 8.337px;
  y: 16.508px;
  fill: var(--svg-color--55486e, #55486E);
  rx: 0.6px;
}

.wstbsmd-b {
  stop-color: var(--svg-color--9e7fbe, #9E7FBE);
}

.wu-lipbol {
  stop-color: var(--svg-color--7b7782, #7B7782);
  stop-opacity: 0;
}

.x7_otxb7w {
  stop-color: var(--svg-color--44395b, #44395B);
  stop-opacity: 0;
}

.x7hmozbub {
  stop-color: var(--svg-color--9e7fbe, #9E7FBE);
  stop-opacity: 0;
}

.x9gflt2ma {
  stop-color: var(--svg-color--2b2c57, #2B2C57);
}

.xf2nv968r {
  stop-color: var(--svg-color--7b7782, #7B7782);
}

.xlx-yobfx {
  stop-color: var(--svg-color--333259, #333259);
}

.y0w3owbag {
  stop-color: var(--svg-color--7a7ba3, #7A7BA3);
  stop-opacity: 0;
}

.y8rleobni {
  d: path("M23.327 6.302c.22.16.41.36.56.61l5.81 10.07c.28.48.11 1.1-.37 1.38l-3.71 2.14c-.48.28-1.1.11-1.38-.37l-.91-1.57z");
}

.ydokdebep {
  stop-color: var(--svg-color--64648d, #64648D);
}

.ydxev5bir {
  stop-color: var(--svg-color--594f74, #594F74);
  stop-opacity: 0;
}

.yw-5m9bmz {
  stop-color: var(--svg-color--44395b, #44395B);
}

.zvlci6bkz {
  stop-color: var(--svg-color--797497, #797497);
  stop-opacity: 0;
}

</style>
