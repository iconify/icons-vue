<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a8u5wi7bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-off-20-regular" /></template>
<style>
.a8u5wi7bl {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708l1.48 1.479A3 3 0 0 0 2 7v6a3 3 0 0 0 3 3h5a3 3 0 0 0 2.932-2.361l4.214 4.215a.5.5 0 0 0 .708-.708zM12 12.707V13a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 1.388-1.905zM12 7v2.879l1 1V8.536l3.605-2.49a.25.25 0 0 1 .392.206v7.495a.25.25 0 0 1-.392.206l-1.716-1.185l2.187 2.186c.509-.14.921-.598.921-1.207V6.252a1.25 1.25 0 0 0-1.96-1.028L13 7.32V7a3 3 0 0 0-3-3H6.121l1 1H10a2 2 0 0 1 2 2");
}

</style>
