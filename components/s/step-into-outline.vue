<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry0isibeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:step-into-outline" /></template>
<style>
.ry0isibeq {
  fill: currentColor;
  d: path("M10.23 20.77Q9.5 20.037 9.5 19t.73-1.77T12 16.5t1.77.73t.73 1.77t-.73 1.77t-1.77.73t-1.77-.73M12 14L7.712 9.712l.688-.708l3.1 3.075V3.212h1v8.886l3.075-3.094l.714.708z");
}

</style>
