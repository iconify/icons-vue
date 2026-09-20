<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4soew-ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:offline-bolt-rounded" /></template>
<style>
.k4soew-ln {
  fill: currentColor;
  d: path("M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22m-.6-8.5v3.425q0 .4.375.488t.575-.263l3.025-5.925q.125-.25-.025-.487t-.425-.238H12.75V7.025q0-.4-.375-.5t-.575.25l-3.15 6q-.125.275.013.5t.412.225z");
}

</style>
