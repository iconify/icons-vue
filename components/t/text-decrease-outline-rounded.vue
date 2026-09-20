<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd12udb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-decrease-outline-rounded" /></template>
<style>
.gd12udb_t {
  fill: currentColor;
  d: path("M15.885 12.5q-.214 0-.357-.143q-.144-.143-.144-.357t.144-.357t.357-.143h6q.213 0 .356.143t.144.357t-.144.357t-.356.143zm-11.69 2.367L2.88 18.16q-.067.158-.189.25q-.12.091-.298.091q-.286 0-.441-.228t-.051-.49l4.9-11.994q.048-.119.156-.204t.246-.084h.362q.144 0 .249.084q.104.085.152.204l4.887 11.943q.104.28-.06.525t-.452.244q-.177 0-.323-.094t-.213-.271l-1.308-3.268zm.359-.967h5.584L7.436 7.1h-.139z");
}

</style>
