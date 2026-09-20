<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx-kc-brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wysiwyg-outline-rounded" /></template>
<style>
.mx-kc-brg {
  fill: currentColor;
  d: path("M5.616 20q-.667 0-1.141-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h12.77q.666 0 1.14.475T20 5.615v12.77q0 .666-.475 1.14t-1.14.475zm0-1h12.769q.269 0 .442-.173t.173-.442V7H5v11.385q0 .269.173.442t.443.173M7.5 11.5q-.213 0-.356-.144T7 10.999t.144-.356t.356-.143h9q.213 0 .356.144t.144.357t-.144.356t-.356.143zm0 4q-.213 0-.356-.144T7 14.999t.144-.356t.356-.143h5q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
