<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGYytZte7W"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="rwjyxgbzi"/><path clip-rule="evenodd" class="wdoivwk-q"/><path class="c1fd7ebzf"/><path clip-rule="evenodd" class="tau1ufbwb"/><path clip-rule="evenodd" class="euy1e0bii"/></g></mask></defs><circle mask="url(#SVGYytZte7W)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:next-track-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.c1fd7ebzf {
  d: path("M17.863 12.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V8.037c0-.908 1.112-1.346 1.731-.682z");
}

.euy1e0bii {
  fill-rule: evenodd;
  d: path("M18.5 7a1 1 0 0 1 1 1v10a1 1 0 1 1-2 0V8a1 1 0 0 1 1-1");
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

.rwjyxgbzi {
  d: path("M12.863 12.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V8.037c0-.908 1.112-1.346 1.731-.682z");
}

.tau1ufbwb {
  fill-rule: evenodd;
  d: path("M15.764 13L13.5 10.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L13.23 7.355c-.62-.664-1.731-.226-1.731.682v9.926c0 .908 1.112 1.346 1.731.682z");
}

.wdoivwk-q {
  fill-rule: evenodd;
  d: path("M10.764 13L8.5 10.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L8.23 7.355c-.62-.664-1.731-.226-1.731.682v9.926c0 .908 1.112 1.346 1.731.682z");
}

</style>
