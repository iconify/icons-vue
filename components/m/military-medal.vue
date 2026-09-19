<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQV46sd)" class="j20s8zbow"/><path fill="url(#ib9Yk9d)" class="j20s8zbow"/><path fill="url(#iCKaJum)" class="ts1rhbfgp"/><path fill="url(#iRaU77G)" class="ts1rhbfgp"/><path fill="url(#ih1wr6d)" class="sk5t1eb_w"/><path fill="url(#i1R89bC)" class="sk5t1eb_w"/><path fill="url(#iWIAoLd)" class="hlpi2rb_m"/><path fill="url(#irNH3Pe)" class="hlpi2rb_m"/><path fill="url(#iIxWxLb)" class="hlpi2rb_m"/><path fill="url(#iKNg6Ud)" class="cusjl3b-o"/><path fill="url(#iH7klOl)" class="cusjl3b-o"/><path fill="url(#i3F1azI)" class="petvt3bph"/><path fill="url(#ilHnQAe)" class="petvt3bph"/><path fill="url(#iMIXckd)" class="n7zbtabbb"/><path fill="url(#ih2TV3b)" class="n7zbtabbb"/><path fill="url(#is05Iwc)" class="n7zbtabbb"/><path fill="url(#iXVzvWb)" class="ozi-k1agn"/><g filter="url(#icM2L3f)"><path fill="url(#iO6Jalb)" class="rdxl0kb8r"/><path fill="url(#ieqgJ3d)" class="rdxl0kb8r"/></g><defs><linearGradient id="iQV46sd" x1="20.305" x2="20.305" y1="2" y2="13.63" gradientUnits="userSpaceOnUse"><stop class="g82l6bc4u"/><stop offset="1" class="vo1co3bst"/></linearGradient><linearGradient id="ib9Yk9d" x1="20.305" x2="20.305" y1="2" y2="3.583" gradientUnits="userSpaceOnUse"><stop class="hj669z69o"/><stop offset="1" class="w4bstlb1b"/></linearGradient><linearGradient id="iCKaJum" x1="11.705" x2="11.705" y1="2" y2="13.63" gradientUnits="userSpaceOnUse"><stop class="g82l6bc4u"/><stop offset="1" class="vo1co3bst"/></linearGradient><linearGradient id="iRaU77G" x1="11.705" x2="11.705" y1="2" y2="3.583" gradientUnits="userSpaceOnUse"><stop class="hj669z69o"/><stop offset="1" class="w4bstlb1b"/></linearGradient><linearGradient id="ih1wr6d" x1="11.601" x2="11.601" y1="2" y2="12.21" gradientUnits="userSpaceOnUse"><stop class="n5b6wk4lr"/><stop offset="1" class="sao9u_bxs"/></linearGradient><linearGradient id="i1R89bC" x1="7.768" x2="8.431" y1="11.108" y2="10.003" gradientUnits="userSpaceOnUse"><stop class="iuxa1v_qb"/><stop offset="1" class="ytfv_ckae"/></linearGradient><linearGradient id="iWIAoLd" x1="27.212" x2="27.212" y1="2" y2="12.21" gradientUnits="userSpaceOnUse"><stop class="n5b6wk4lr"/><stop offset="1" class="sao9u_bxs"/></linearGradient><linearGradient id="irNH3Pe" x1="27.308" x2="24.625" y1="6.669" y2="6.669" gradientUnits="userSpaceOnUse"><stop class="ma9d34l1l"/><stop offset="1" class="thlqik77f"/></linearGradient><linearGradient id="iIxWxLb" x1="24.719" x2="23.977" y1="11.234" y2="9.908" gradientUnits="userSpaceOnUse"><stop class="iuxa1v_qb"/><stop offset="1" class="ytfv_ckae"/></linearGradient><linearGradient id="iKNg6Ud" x1="16" x2="16" y1="2" y2="13.63" gradientUnits="userSpaceOnUse"><stop class="jpw64dbhn"/><stop offset="1" class="mg8pn3dwn"/></linearGradient><linearGradient id="iH7klOl" x1="16" x2="16" y1="2" y2="3.248" gradientUnits="userSpaceOnUse"><stop class="b_7m79bho"/><stop offset="1" class="qw5873b0m"/></linearGradient><linearGradient id="i3F1azI" x1="21.367" x2="13.304" y1="16.063" y2="29.688" gradientUnits="userSpaceOnUse"><stop class="zyy2sebfb"/><stop offset="1" class="a3ao8sbxc"/></linearGradient><linearGradient id="ilHnQAe" x1="12.492" x2="14.867" y1="30.5" y2="17.063" gradientUnits="userSpaceOnUse"><stop class="noy6u8_5o"/><stop offset="1" class="k_q28_b4b"/></linearGradient><linearGradient id="iMIXckd" x1="12.195" x2="24.472" y1="18.64" y2="18.64" gradientUnits="userSpaceOnUse"><stop class="ehyg8wqsg"/><stop offset="1" class="vqbzr5d3f"/></linearGradient><linearGradient id="iXVzvWb" x1="24.055" x2="16.01" y1="18.13" y2="18.13" gradientUnits="userSpaceOnUse"><stop class="u3fznriir"/><stop offset="1" class="ep_ctkm6f"/><stop offset="1" class="ep_ctkm6f"/></linearGradient><linearGradient id="iO6Jalb" x1="15.142" x2="18.363" y1="17.79" y2="24.148" gradientUnits="userSpaceOnUse"><stop class="y09wzybtv"/><stop offset="1" class="hgk_o0bxr"/></linearGradient><radialGradient id="ih2TV3b" cx="0" cy="0" r="1" gradientTransform="matrix(-10.9797 0 0 -9.59463 19.191 19.71)" gradientUnits="userSpaceOnUse"><stop offset=".844" class="g23k9-bem"/><stop offset="1" class="nvqwiabcw"/></radialGradient><radialGradient id="is05Iwc" cx="0" cy="0" r="1" gradientTransform="matrix(10.3667 0 0 9.34393 13.863 19.71)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="p8rhe369k"/><stop offset="1" class="feq4hk7pc"/></radialGradient><radialGradient id="ieqgJ3d" cx="0" cy="0" r="1" gradientTransform="rotate(130.746 5.33 12.616)scale(2.68113 3.65655)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vv5ow_bjb"/><stop offset="1" class="td3nbtbdl"/></radialGradient><filter id="icM2L3f" width="9.224" height="8.899" x="11.305" y="14.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.14902 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.372549 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_1377" result="effect2_innerShadow_18_1377"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:military-medal" /></template>
<style>
.a3ao8sbxc {
  stop-color: var(--svg-color--dc9729, #DC9729);
}

.b_7m79bho {
  stop-color: var(--svg-color--eb3a52, #EB3A52);
}

.cusjl3b-o {
  d: path("M19 2h-6v11.63h6z");
}

.ehyg8wqsg {
  stop-color: var(--svg-color--faa945, #FAA945);
}

.ep_ctkm6f {
  stop-color: var(--svg-color--faa742, #FAA742);
}

.feq4hk7pc {
  stop-color: var(--svg-color--d2801f, #D2801F);
}

.ft5dv1b6b {
  fill: none;
}

.g23k9-bem {
  stop-color: var(--svg-color--f7b44d, #F7B44D);
  stop-opacity: 0;
}

.g82l6bc4u {
  stop-color: var(--svg-color--d6c6e5, #D6C6E5);
}

.hgk_o0bxr {
  stop-color: var(--svg-color--5d3247, #5D3247);
}

.hj669z69o {
  stop-color: var(--svg-color--ccc1d8, #CCC1D8);
}

.hlpi2rb_m {
  d: path("M21.61 2h3.29c.61 0 1.11.51 1.11 1.14v5.79c0 .4-.21.78-.55.98l-3.85 2.3z");
}

.iuxa1v_qb {
  stop-color: var(--svg-color--3856bb, #3856BB);
}

.j20s8zbow {
  d: path("M19 2v11.63l2.61-1.42V2z");
}

.jpw64dbhn {
  stop-color: var(--svg-color--f2415a, #F2415A);
}

.k_q28_b4b {
  stop-color: var(--svg-color--fa8547, #FA8547);
  stop-opacity: 0;
}

.ma9d34l1l {
  stop-color: var(--svg-color--53baff, #53BAFF);
}

.mg8pn3dwn {
  stop-color: var(--svg-color--e83973, #E83973);
}

.n5b6wk4lr {
  stop-color: var(--svg-color--3ea2f8, #3EA2F8);
}

.n7zbtabbb {
  d: path("M16 28.15c4.545 0 8.23-3.779 8.23-8.44s-3.685-8.44-8.23-8.44s-8.23 3.779-8.23 8.44s3.685 8.44 8.23 8.44");
}

.noy6u8_5o {
  stop-color: var(--svg-color--fa8547, #FA8547);
}

.nvqwiabcw {
  stop-color: var(--svg-color--f7b44d, #F7B44D);
}

.ozi-k1agn {
  d: path("M16.01 28.76c-2.36 0-4.58-.94-6.24-2.65a9.1 9.1 0 0 1-2.59-6.4c0-2.42.92-4.69 2.59-6.4a8.69 8.69 0 0 1 12.49 0c3.44 3.53 3.44 9.27 0 12.8c-1.68 1.71-3.9 2.65-6.25 2.65M16 11.89c-1.95 0-3.91.76-5.39 2.29a7.87 7.87 0 0 0-2.23 5.53c0 2.09.79 4.05 2.23 5.53A7.48 7.48 0 0 0 16 27.53c2.04 0 3.95-.81 5.39-2.29c2.97-3.05 2.97-8.01 0-11.06A7.46 7.46 0 0 0 16 11.89");
}

.p8rhe369k {
  stop-color: var(--svg-color--d2801f, #D2801F);
  stop-opacity: 0;
}

.petvt3bph {
  d: path("M16 30c5.545 0 10.04-4.607 10.04-10.29S21.545 9.42 16 9.42S5.96 14.027 5.96 19.71S10.455 30 16 30");
}

.qw5873b0m {
  stop-color: var(--svg-color--eb3a52, #EB3A52);
  stop-opacity: 0;
}

.rdxl0kb8r {
  d: path("m16.61 15.66l.83 1.72c.1.2.29.35.51.38l1.85.28c.55.08.78.78.37 1.18l-1.28 1.28c-.19.19-.25.47-.17.73l.59 1.71c.2.57-.36 1.11-.91.87l-2.14-.96a.64.64 0 0 0-.54 0l-2.14.96c-.54.24-1.11-.3-.91-.87l.59-1.71c.09-.26.02-.54-.17-.73l-1.28-1.28c-.4-.4-.18-1.1.37-1.18l1.85-.28c.22-.03.41-.17.51-.38l.83-1.72c.27-.52.99-.52 1.24 0");
}

.sao9u_bxs {
  stop-color: var(--svg-color--3363c1, #3363C1);
}

.sk5t1eb_w {
  d: path("M10.4 2H7.11C6.5 2 6 2.51 6 3.14v5.79c0 .4.21.78.55.98l3.85 2.3z");
}

.td3nbtbdl {
  stop-color: var(--svg-color--602543, #602543);
  stop-opacity: 0;
}

.thlqik77f {
  stop-color: var(--svg-color--53baff, #53BAFF);
  stop-opacity: 0;
}

.ts1rhbfgp {
  d: path("M10.4 2v10.21l2.61 1.42L13 2z");
}

.u3fznriir {
  stop-color: var(--svg-color--f9a842, #F9A842);
}

.vo1co3bst {
  stop-color: var(--svg-color--d3bbe0, #D3BBE0);
}

.vqbzr5d3f {
  stop-color: var(--svg-color--ec9936, #EC9936);
}

.vv5ow_bjb {
  stop-color: var(--svg-color--602543, #602543);
}

.w4bstlb1b {
  stop-color: var(--svg-color--ccc1d8, #CCC1D8);
  stop-opacity: 0;
}

.y09wzybtv {
  stop-color: var(--svg-color--864b60, #864B60);
}

.ytfv_ckae {
  stop-color: var(--svg-color--3856bb, #3856BB);
  stop-opacity: 0;
}

.zyy2sebfb {
  stop-color: var(--svg-color--f4c654, #F4C654);
}

</style>
