<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffwk9frog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-connected-no-internet-0-bar" /></template>
<style>
.ffwk9frog {
  fill: currentColor;
  d: path("M3 21L21 3v4.23h-1V5.422L5.421 20H17.5v1zm16.98.02q-.21-.209-.21-.52t.21-.52q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.02-3.25V9.615h1v8.153z");
}

</style>
