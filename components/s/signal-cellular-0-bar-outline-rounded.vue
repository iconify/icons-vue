<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw3e4gbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-0-bar-outline-rounded" /></template>
<style>
.zw3e4gbql {
  fill: currentColor;
  d: path("M4.425 22q-.675 0-.937-.612T3.7 20.3L20.3 3.7q.475-.475 1.088-.213t.612.938V20.5q0 .625-.437 1.063T20.5 22zm2.4-2H20V6.85z");
}

</style>
