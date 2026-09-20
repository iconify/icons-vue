<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3vsev8zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:notification-audio-off-sharp" /></template>
<style>
.g3vsev8zq {
  fill: currentColor;
  d: path("M16.442 12.616V7.385h.885v5.23zm-2.326-1.308V8.692H15v2.616zm4.653 0V8.692h.885v2.616zm1.185 10.523l-3.067-3.062H5v-1h1.616V9.846q0-.592.125-1.162q.126-.57.378-1.103l2.266 2.265H7.969l-5.3-5.294l.708-.713l17.285 17.284zM12 21.385q-.671 0-1.143-.472t-.472-1.144h3.23q0 .672-.472 1.144T12 21.385M11.921 9.5L8.316 5.894q.557-.521 1.238-.866T11 4.546V3h2v1.546q.575.093 1.071.307t.952.507q-1.279.52-2.116 1.615T11.92 9.5");
}

</style>
