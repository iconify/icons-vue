<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGQBnnlcgv"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="r0gxw56ki"/><path class="q8loy-b5i"/></g></mask></defs><circle mask="url(#SVGQBnnlcgv)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:music-note-single-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
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

.q8loy-b5i {
  d: path("M13 7a1 1 0 0 1 1 1v10a1 1 0 1 1-2 0V8a1 1 0 0 1 1-1");
}

.r0gxw56ki {
  d: path("M12.781 4.698c4.323 2.937 6.469 5.064 6.469 6.606c0 1.492-.82 2.7-2.396 3.583c-.436.245-.922-.232-.685-.672c.407-.758.273-1.607-.461-2.617c-.774-1.065-1.89-1.84-3.365-2.328A.5.5 0 0 1 12 8.795V5.111a.5.5 0 0 1 .781-.413M10.75 20.75c-1.77 0-3.25-1.143-3.25-2.625S8.98 15.5 10.75 15.5S14 16.643 14 18.125s-1.48 2.625-3.25 2.625");
}

</style>
