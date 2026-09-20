<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yuwr0yb3y"/><path fill="url(#SVGCbxSOcvU)" class="eovdkccqf"/><path fill="url(#SVGfQUELdtM)" class="vnh55b-zh"/><path fill="url(#SVGHe0UkdMv)" class="btblmbbwb"/><defs><linearGradient id="SVGCbxSOcvU" x1="2.531" x2="22.545" y1="7.504" y2="9.149" gradientUnits="userSpaceOnUse"><stop class="ytmspcbgh"/><stop offset="1" class="ni6iokbel"/></linearGradient><linearGradient id="SVGfQUELdtM" x1="2.995" x2="23.489" y1="8.133" y2="10.112" gradientUnits="userSpaceOnUse"><stop class="hlo1iubsn"/><stop offset="1" class="vjcvqybpw"/></linearGradient><linearGradient id="SVGHe0UkdMv" x1="6.375" x2="11.438" y1="15.937" y2="16.781" gradientUnits="userSpaceOnUse"><stop class="vcdv8bc1i"/><stop offset="1" class="dujxl1bxh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mf" /></template>
<style>
.btblmbbwb {
  d: path("M7.612 17.89a1.53 1.53 0 0 1-1.215-1.778c.146-.85.883-1.43 1.693-1.277l1.547.275a1.53 1.53 0 0 1 1.214 1.778c-.146.85-.883 1.429-1.693 1.277z");
}

.dujxl1bxh {
  stop-color: var(--svg-color--6d6bfa, #6d6bfa);
}

.eovdkccqf {
  d: path("M8.77 9.486a1.58 1.58 0 0 1-1.254-1.8a1.524 1.524 0 0 1 1.75-1.294l7.65 1.373a1.58 1.58 0 0 1 1.254 1.8a1.524 1.524 0 0 1-1.75 1.293z");
}

.ft5dv1b6b {
  fill: none;
}

.hlo1iubsn {
  stop-color: var(--svg-color--2ff3f9, #2ff3f9);
}

.ni6iokbel {
  stop-color: var(--svg-color--fe38a3, #fe38a3);
}

.vcdv8bc1i {
  stop-color: var(--svg-color--ba74ff, #ba74ff);
}

.vjcvqybpw {
  stop-color: var(--svg-color--0abcfe, #0abcfe);
}

.vnh55b-zh {
  d: path("M8.157 13.872a1.5 1.5 0 0 1-1.192-1.755a1.48 1.48 0 0 1 1.721-1.215l4.9.912c.826.151 1.35.956 1.198 1.755a1.48 1.48 0 0 1-1.14 1.203a1.5 1.5 0 0 1-.582.011z");
}

.ytmspcbgh {
  stop-color: var(--svg-color--ff5b5d, #ff5b5d);
}

.yuwr0yb3y {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M7.18 3h9.64C19.105 3 21 4.935 21 7.348v9.304C21 19.026 19.144 21 16.82 21H7.18C4.895 21 3 19.065 3 16.652V7.348C3 4.93 4.856 3 7.18 3");
}

</style>
