<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r80budugd"/><path fill="url(#SVGDTGiJcJE)" class="ed4wejbwm"/><path class="suiwxzp_j"/><path class="d4yco_i7v"/><path fill="url(#SVGg4NArQYV)" class="c-vm_1bti"/><defs><linearGradient id="SVGDTGiJcJE" x1="3.001" x2="23.62" y1="18.878" y2="11.267" gradientUnits="userSpaceOnUse"><stop class="zji0a49xo"/><stop offset=".84" class="rcs-5tbwd"/><stop offset="1" class="ss9u4ybtw"/></linearGradient><linearGradient id="SVGg4NArQYV" x1="6.036" x2="13.687" y1="17.183" y2="11.338" gradientUnits="userSpaceOnUse"><stop class="qaveelk9k"/><stop offset=".72" class="get9g6bfs"/><stop offset="1" class="b8534puqy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rtm" /></template>
<style>
.b8534puqy {
  stop-color: var(--svg-color--222, #222);
}

.c-vm_1bti {
  d: path("M6.976 16.53c-1.227 0-2.296-.376-2.678-.562a4.93 4.93 0 0 0 4.067 2.065c2.79 0 4.67-3.77 4.67-5.49c0-1.38-.394-1.981-.597-2.11c.343 4.674-3.932 6.098-5.462 6.098");
}

.d4yco_i7v {
  fill: var(--svg-color--fd5c27, #fd5c27);
  d: path("M3.719 20.438c-1.238-2.278-.602-3.932-.124-4.472c.079.506.4 1.614 1.08 1.94c-.787.321-.967 1.823-.956 2.532");
}

.ed4wejbwm {
  d: path("M4.658 8.163c-1.434 1.502-1.294 4.911-1.069 6.413l1.238-1.58c2.115-3.505 6.408-4.63 7.06-4.838c.529-.158 3.904-1.328 5.53-1.89c.973-.636 1.997-2.07 2.391-2.706c-.675.596-2.892 1.389-6.447 1.66c-3.56.263-6.627.759-8.708 2.941z");
}

.ft5dv1b6b {
  fill: none;
}

.get9g6bfs {
  stop-color: var(--svg-color--7d6356, #7d6356);
}

.qaveelk9k {
  stop-color: var(--svg-color--e4713a, #e4713a);
}

.r80budugd {
  fill: var(--svg-color--0b0d0c, #0b0d0c);
  d: path("M9.946 11.793c-2.543.247-3.646 2.03-3.882 2.891c.112.135.608.405 1.721.405c1.396 0 2.712-1.502 2.16-3.296m5.389-3.038a5.8 5.8 0 0 1-2.51.793c.552.113 2.054.169 3.618-.478a13 13 0 0 0 3.179-1.879c.337-.259 1.08-.799 1.378-.872c-1.536-.096-4.54 1.716-5.665 2.436");
}

.rcs-5tbwd {
  stop-color: var(--svg-color--736155, #736155);
}

.ss9u4ybtw {
  stop-color: var(--svg-color--372e2a, #372e2a);
}

.suiwxzp_j {
  fill: var(--svg-color--0b0d0c, #0b0d0c);
  d: path("M8.055 11.119c-2.132.827-3.1 1.637-3.319 1.94c1.654-2.767 4.821-4.246 6.2-4.646l6.509-2.138c-2.678 2.093-6.729 3.814-9.395 4.844z");
}

.zji0a49xo {
  stop-color: var(--svg-color--fc5716, #fc5716);
}

</style>
