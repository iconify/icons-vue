<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGL8VIJc7t)" class="hdhez1_8w"/><path class="mfrfpbcke"/><path class="hbu4di2jk"/><path fill="url(#SVGlexVlv3P)" class="xqct17b4q"/><defs><linearGradient id="SVGL8VIJc7t" x1="18.91" x2="8.168" y1="6.797" y2="17.985" gradientUnits="userSpaceOnUse"><stop offset=".01" class="gie7_kb_y"/><stop offset=".3" class="ch61-kboh"/><stop offset=".91" class="rt0h2wbfp"/><stop offset="1" class="csi8sh-az"/></linearGradient><linearGradient id="SVGlexVlv3P" x1="3.169" x2="5.556" y1="10.55" y2="10.562" gradientUnits="userSpaceOnUse"><stop class="ncuvdyb8w"/><stop offset="1" class="swlddef3z"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:yam" /></template>
<style>
.ch61-kboh {
  stop-color: var(--svg-color--ed4892, #ed4892);
}

.csi8sh-az {
  stop-color: var(--svg-color--b91f2b, #b91f2b);
}

.ft5dv1b6b {
  fill: none;
}

.gie7_kb_y {
  stop-color: var(--svg-color--f374ab, #f374ab);
}

.hbu4di2jk {
  fill: var(--svg-color--e6de95, #e6de95);
  d: path("M9.104 7.629c3.033-1.847 5.232-3.789 4.91-4.337c-.32-.548-3.039.505-6.072 2.352S2.71 9.432 3.032 9.98c.32.548 3.039-.505 6.072-2.351");
}

.hdhez1_8w {
  d: path("M3.515 11.65a4 4 0 0 1-.47-1.916c3.221-2.133 9.812-6.423 10.4-6.504c.409-.07.83-.004 1.199.186c5.02 5.762 6.07 10.578 6.324 13.707c.118.822-.03 2.64-1.533 3.375c-1.88.928-3.487-.222-4.791-.531c-1.299-.316-3.957-1.33-5.188-2.121c-1.224-.797-1.712-1.403-2.38-2.028c-.674-.63-3.054-3.283-3.561-4.167");
}

.mfrfpbcke {
  fill: var(--svg-color--ebddd5, #ebddd5);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M16.684 6.729c.241-.334.643.185.816.482c1.49 1.91 2.844 6.102 2.789 6.102c-.415-1.335-3.895-6.17-3.605-6.584");
}

.ncuvdyb8w {
  stop-color: var(--svg-color--eac4cf, #eac4cf);
}

.rt0h2wbfp {
  stop-color: var(--svg-color--a71c2d, #a71c2d);
}

.swlddef3z {
  stop-color: var(--svg-color--e76d9e, #e76d9e);
  stop-opacity: 0;
}

.xqct17b4q {
  d: path("M3.17 10.73c-.15-.137-.056-.347.012-.434c.47.223 2.09-.197 2.844-.432c-.89.34-2.708 1.001-2.857.865");
}

</style>
