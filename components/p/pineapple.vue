<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBsZ9bc)" class="kwodi8bgb"/><g filter="url(#iSHBpSb)"><path fill="url(#iXNyQBb)" class="a_qxvzs7l"/></g><g filter="url(#i44075b)"><path fill="url(#iUDWLhz)" class="wlo7zibvj"/></g><path fill="url(#ielXUnd)" class="ii4jv8cbp"/><g filter="url(#i97kLqe)"><path fill="url(#iQlPxze)" class="ag63vvbxn"/></g><g filter="url(#ijk6Abd)"><path fill="url(#iELY7Id)" class="y9bzn9bmd"/></g><path fill="url(#idonQ3J)" class="h4npe9bab"/><g filter="url(#i9hmeVL)"><path fill="url(#ihv0k0b)" class="jsxdgjb4z"/></g><g filter="url(#inO7gXl)"><path class="fo2j698wd"/></g><path fill="url(#ixmJagd)" clip-rule="evenodd" class="rkxn01yjw"/><path fill="url(#ie2Bivt)" clip-rule="evenodd" class="rkxn01yjw"/><path fill="url(#iVVq9me)" clip-rule="evenodd" class="rkxn01yjw"/><path class="jz4quabhr"/><defs><linearGradient id="iBsZ9bc" x1="8.431" x2="12.133" y1="2.581" y2="7.034" gradientUnits="userSpaceOnUse"><stop class="zk8yv5bol"/><stop offset="1" class="c2ce00i4z"/></linearGradient><linearGradient id="iXNyQBb" x1="8.44" x2="12.095" y1="2.648" y2="6.734" gradientUnits="userSpaceOnUse"><stop class="zl2psxbzl"/><stop offset="1" class="bixnc3bmy"/></linearGradient><linearGradient id="iUDWLhz" x1="8.44" x2="12.095" y1="2.648" y2="6.734" gradientUnits="userSpaceOnUse"><stop class="cg9k11f6w"/><stop offset="1" class="c3fpi9btk"/></linearGradient><linearGradient id="ielXUnd" x1="12.366" x2="14.527" y1="3.611" y2="7.159" gradientUnits="userSpaceOnUse"><stop class="zk8yv5bol"/><stop offset="1" class="c2ce00i4z"/></linearGradient><linearGradient id="iQlPxze" x1="12.366" x2="14.527" y1="3.611" y2="7.159" gradientUnits="userSpaceOnUse"><stop class="zl2psxbzl"/><stop offset="1" class="bixnc3bmy"/></linearGradient><linearGradient id="iELY7Id" x1="14.168" x2="12.118" y1="2.737" y2="9.13" gradientUnits="userSpaceOnUse"><stop class="bqwu6uijh"/><stop offset="1" class="czqfq7bfh"/></linearGradient><linearGradient id="idonQ3J" x1="7.977" x2="7.211" y1="6.715" y2="10.098" gradientUnits="userSpaceOnUse"><stop class="zk8yv5bol"/><stop offset="1" class="c2ce00i4z"/></linearGradient><linearGradient id="ihv0k0b" x1="5.392" x2="10.914" y1="7.625" y2="9.797" gradientUnits="userSpaceOnUse"><stop class="zl2psxbzl"/><stop offset="1" class="bixnc3bmy"/></linearGradient><filter id="iSHBpSb" width="4.495" height="7.796" x="7.527" y="2.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29304" stdDeviation=".25"/></filter><filter id="i44075b" width="4.401" height="7.795" x="7.621" y="2.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29304" stdDeviation=".25"/></filter><filter id="i97kLqe" width="4.329" height="8.28" x="10.921" y="1.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29304" stdDeviation=".25"/></filter><filter id="ijk6Abd" width="3.5" height="8.28" x="11.321" y="1.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29304" stdDeviation=".25"/></filter><filter id="i9hmeVL" width="7.881" height="4.235" x="4.01" y="6.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29304" stdDeviation=".25"/></filter><filter id="inO7gXl" width="6.743" height="3.777" x="5.147" y="6.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29304" stdDeviation=".25"/></filter><radialGradient id="ixmJagd" cx="0" cy="0" r="1" gradientTransform="rotate(113.288 4.28 12.865)scale(16.3759 14.3546)" gradientUnits="userSpaceOnUse"><stop class="s_5y4gbbo"/><stop offset=".672" class="kx4ayt75j"/><stop offset="1" class="v23hrg0hk"/></radialGradient><radialGradient id="ie2Bivt" cx="0" cy="0" r="1" gradientTransform="matrix(6.05467 13.22589 -11.59333 5.3073 14.428 15.797)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="lxe4xfbok"/><stop offset=".82" class="nv1uoacub"/><stop offset="1" class="i645-hbzz"/></radialGradient><radialGradient id="iVVq9me" cx="0" cy="0" r="1" gradientTransform="matrix(16.74844 12.661 -11.09818 14.68108 7.804 12.614)" gradientUnits="userSpaceOnUse"><stop class="x-vccfb9o"/><stop offset=".505" class="a9wnzqlxi"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pineapple" /></template>
<style>
.a_qxvzs7l {
  d: path("M8.121 2.507c2.36 1.479 3.867 3.497 3.27 6.795c-2.843-1.82-3.668-3.696-3.27-6.795");
}

.a9wnzqlxi {
  stop-color: var(--svg-color--fca968, #FCA968);
  stop-opacity: 0;
}

.ag63vvbxn {
  d: path("M14.321 2.47c-2.69 1.47-3.482 4.296-2.487 7.28c2.578-1.628 3.561-4.217 2.487-7.28");
}

.bixnc3bmy {
  stop-color: var(--svg-color--addf28, #ADDF28);
}

.bqwu6uijh {
  stop-color: var(--svg-color--c7f481, #C7F481);
}

.c2ce00i4z {
  stop-color: var(--svg-color--98c71b, #98C71B);
}

.c3fpi9btk {
  stop-color: var(--svg-color--cbf07f, #CBF07F);
  stop-opacity: 0;
}

.cg9k11f6w {
  stop-color: var(--svg-color--cbf07f, #CBF07F);
}

.czqfq7bfh {
  stop-color: var(--svg-color--c7f481, #C7F481);
  stop-opacity: 0;
}

.fo2j698wd {
  fill: var(--svg-color--cff278, #CFF278);
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M5.647 7.198c2.36-.54 3.839 0 5.744 2.588c-2.303-1.82-3.128-2.218-5.744-2.588");
}

.ft5dv1b6b {
  fill: none;
}

.h4npe9bab {
  d: path("M4 7c2.948-1.398 6.508-.06 7.953 2.988C9.001 11.376 5.441 10.038 4 7");
}

.i645-hbzz {
  stop-color: var(--svg-color--d03e6b, #D03E6B);
  stop-opacity: 0.8;
}

.ii4jv8cbp {
  d: path("M14.455 2.042c-2.948 1.398-4.165 5-2.72 8.05c2.944-1.409 4.161-5.011 2.72-8.05");
}

.jsxdgjb4z {
  d: path("M4.51 7.17c2.701-.825 5.203 0 6.88 2.616c-3.098.91-5.202-.228-6.88-2.616");
}

.jz4quabhr {
  fill: var(--svg-color--f3851e, #F3851E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("m13.029 10.546l2.131 1.336a.255.255 0 0 0 .39-.185l.312-2.529a.26.26 0 0 0-.117-.246l-.068-.047a7.2 7.2 0 0 0-2.63.329l-.14 1.086a.28.28 0 0 0 .122.256m-4.714 1.807a7.2 7.2 0 0 1 1.906-1.809l.918.596a.26.26 0 0 1 .117.247l-.315 2.496a.255.255 0 0 1-.389.184l-2.131-1.335a.28.28 0 0 1-.122-.256zm2.442 13.871a7 7 0 0 1-.274-.522l-1.715-3.617c.064-.14.235-.225.366-.133l2.132 1.335a.26.26 0 0 1 .117.247l-.315 2.495c-.021.145-.17.222-.311.195m5.031 3.506a7.3 7.3 0 0 1-2.67-1.035l-.004-.047l.313-2.518a.255.255 0 0 1 .389-.184l2.131 1.335a.22.22 0 0 1 .117.246zm9.474-6.726a7.3 7.3 0 0 1-.906 2.697l-1.92-1.195a.26.26 0 0 1-.117-.247l.315-2.495a.255.255 0 0 1 .389-.185l2.16 1.35c.034.018.06.046.08.075m-2.356-7.621l1.714 3.615q.125.267.23.538c-.058.126-.234.216-.366.13l-2.131-1.335a.26.26 0 0 1-.117-.247l.315-2.495c.021-.166.208-.26.355-.206m-11.686 1.932L9.09 15.98a.255.255 0 0 0-.389.184l-.315 2.496a.26.26 0 0 0 .117.246l2.132 1.335a.255.255 0 0 0 .388-.184l.315-2.495a.22.22 0 0 0-.117-.247m4.022.741a.255.255 0 0 0 .389-.184l.315-2.496a.26.26 0 0 0-.117-.246l-2.132-1.336a.255.255 0 0 0-.389.185l-.314 2.495a.26.26 0 0 0 .116.247zm4.599-2.181a.255.255 0 0 0 .389-.184l.314-2.496a.26.26 0 0 0-.117-.246l-2.131-1.335a.255.255 0 0 0-.389.184l-.315 2.495a.26.26 0 0 0 .117.247zm-3.968 5.227l-2.131-1.336a.255.255 0 0 0-.39.185l-.314 2.495a.26.26 0 0 0 .117.247l2.131 1.335a.255.255 0 0 0 .39-.184l.314-2.496a.26.26 0 0 0-.117-.246m4.599-2.182l-2.131-1.335a.255.255 0 0 0-.39.185l-.314 2.495a.26.26 0 0 0 .117.247l2.131 1.335a.255.255 0 0 0 .39-.184l.314-2.496a.26.26 0 0 0-.117-.246m-2.049 4.839a.255.255 0 0 0-.389.184l-.315 2.496a.26.26 0 0 0 .117.246l2.132 1.336a.255.255 0 0 0 .389-.184l.314-2.496a.26.26 0 0 0-.116-.246z");
}

.kwodi8bgb {
  d: path("M7.9 2.007c3.12 1.193 4.795 4.724 3.743 7.895C8.532 8.705 6.858 5.174 7.9 2.007");
}

.kx4ayt75j {
  stop-color: var(--svg-color--ffa46b, #FFA46B);
}

.lxe4xfbok {
  stop-color: var(--svg-color--ffab6f, #FFAB6F);
  stop-opacity: 0;
}

.nv1uoacub {
  stop-color: var(--svg-color--e97766, #E97766);
  stop-opacity: 0.2;
}

.rkxn01yjw {
  fill-rule: evenodd;
  d: path("M15.678 8.875a7.2 7.2 0 0 0-3.534.686l-1.072.508q-.447.212-.851.475a7.215 7.215 0 0 0-2.588 9.147l1.135 2.394l1.715 3.617q.127.27.274.522a7.2 7.2 0 0 0 2.361 2.47a7.3 7.3 0 0 0 2.67 1.036a7.2 7.2 0 0 0 4.327-.593l1.071-.508a7.2 7.2 0 0 0 3.17-2.928a7.3 7.3 0 0 0 .906-2.697a7.2 7.2 0 0 0-.64-4.006l-1.715-3.615l-1.137-2.397a7.22 7.22 0 0 0-6.092-4.11");
}

.s_5y4gbbo {
  stop-color: var(--svg-color--ffe79e, #FFE79E);
}

.v23hrg0hk {
  stop-color: var(--svg-color--f0906d, #F0906D);
}

.wlo7zibvj {
  d: path("M8.121 2.507c2.36 1.478 3.867 3.497 3.27 6.795c-.825-3.07-1.678-4.293-3.27-6.795");
}

.x-vccfb9o {
  stop-color: var(--svg-color--b68450, #B68450);
  stop-opacity: 0.6;
}

.y9bzn9bmd {
  d: path("M14.321 2.47c-1.546 1.968-2.634 4.24-2.487 7.28c1.596-2.52 2.487-4.889 2.487-7.28");
}

.zk8yv5bol {
  stop-color: var(--svg-color--7db41c, #7DB41C);
}

.zl2psxbzl {
  stop-color: var(--svg-color--90cb27, #90CB27);
}

</style>
