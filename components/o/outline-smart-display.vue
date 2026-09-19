<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_6gj9cl"/><path class="xo4-747so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-smart-display" /></template>
<style>
.gf_6gj9cl {
  fill: currentColor;
  d: path("M9.5 7.5v9l7-4.5z");
}

.xo4-747so {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14.01H4V5.99h16z");
}

</style>
