<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msvxjqg9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-2-bar" /></template>
<style>
.msvxjqg9f {
  fill: currentColor;
  d: path("M10.908 19.977q-.446-.446-.446-1.092t.446-1.093T12 17.346t1.092.446t.446 1.093t-.446 1.092t-1.092.446t-1.092-.446M6.35 15.35l-1.023-1.034q1.302-1.302 3.001-2.04q1.699-.737 3.672-.737t3.672.74t3.001 2.048L17.65 15.35q-1.1-1.1-2.55-1.725T12 13t-3.1.625t-2.55 1.725");
}

</style>
