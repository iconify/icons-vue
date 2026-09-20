<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGnE4Mpd0c"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="l4k3nybci"/><path class="kg14lbomy"/><path class="st5bidc6a"/><path class="bb4n9g22l"/></g></mask></defs><circle mask="url(#SVGnE4Mpd0c)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:rewind-time-circle-filled" /></template>
<style>
.bb4n9g22l {
  d: path("M17 13.5a1 1 0 0 1-1 1h-3a1 1 0 1 1 0-2h3a1 1 0 0 1 1 1");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kg14lbomy {
  d: path("M6.967 14.695a1 1 0 0 1-1.412.082l-1.72-1.53a1 1 0 0 1 1.33-1.494l1.72 1.53a1 1 0 0 1 .082 1.412");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.l4k3nybci {
  d: path("M8.955 8.805a5.94 5.94 0 0 0-1.736 4.87a1 1 0 0 1-1.99.21a7.94 7.94 0 0 1 2.322-6.504c3.136-3.092 8.19-3.04 11.289.102s3.081 8.198-.054 11.29a7.92 7.92 0 0 1-5.44 2.286a8 8 0 0 1-2.283-.29a1 1 0 1 1 .533-1.927a6 6 0 0 0 1.714.217a5.92 5.92 0 0 0 4.071-1.71c2.343-2.31 2.365-6.099.035-8.461s-6.118-2.393-8.46-.083");
}

.st5bidc6a {
  d: path("M5.42 14.6a1 1 0 0 0 1.4.2l2-1.5a1 1 0 0 0-1.2-1.6l-2 1.5a1 1 0 0 0-.2 1.4M13 9a1 1 0 0 1 1 1v3.5a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1");
}

</style>
