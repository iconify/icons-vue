<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGUgGUNe6Y"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="zlpxmnbao"/><path clip-rule="evenodd" class="xwdqv2bsf"/><path class="qyf-1n63u"/><path clip-rule="evenodd" class="a-mnc9dvl"/><path clip-rule="evenodd" class="enov0h9ru"/></g></mask></defs><circle mask="url(#SVGUgGUNe6Y)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:previous-track-circle-filled" /></template>
<style>
.a-mnc9dvl {
  fill-rule: evenodd;
  d: path("m10.236 13l2.264-2.426v4.852zm-2.1.682a1 1 0 0 1 0-1.364l4.633-4.963c.62-.664 1.731-.226 1.731.682v9.926c0 .908-1.112 1.346-1.731.682z");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.enov0h9ru {
  fill-rule: evenodd;
  d: path("M7.5 7a1 1 0 0 0-1 1v10a1 1 0 1 0 2 0V8a1 1 0 0 0-1-1");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.qyf-1n63u {
  d: path("M8.137 12.318a1 1 0 0 0 0 1.364l4.632 4.963c.62.664 1.731.226 1.731-.682V8.037c0-.908-1.112-1.346-1.731-.682z");
}

.xwdqv2bsf {
  fill-rule: evenodd;
  d: path("m15.236 13l2.264-2.426v4.852zm-2.1.682a1 1 0 0 1 0-1.364l4.633-4.963c.62-.664 1.731-.226 1.731.682v9.926c0 .908-1.112 1.346-1.731.682z");
}

.zlpxmnbao {
  d: path("M13.137 12.318a1 1 0 0 0 0 1.364l4.632 4.963c.62.664 1.731.226 1.731-.682V8.037c0-.908-1.112-1.346-1.731-.682z");
}

</style>
