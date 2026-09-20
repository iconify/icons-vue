<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k57f9ob8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-remote-sharp" /></template>
<style>
.k57f9ob8h {
  fill: currentColor;
  d: path("M8 23V9h8v14zm4-8.75q.525 0 .888-.363T13.25 13t-.363-.888T12 11.75t-.888.363t-.362.887t.363.888t.887.362m-3.55-6.8l-1.4-1.4q1-1 2.275-1.525T12 4t2.675.525T16.95 6.05l-1.4 1.4q-.725-.725-1.637-1.088T12 6t-1.912.363T8.45 7.45m-2.8-2.8L4.2 3.2Q5.775 1.675 7.788.837T12 0t4.213.838T19.75 3.25l-1.4 1.4q-1.25-1.3-2.9-1.975T12 2t-3.45.675t-2.9 1.975");
}

</style>
