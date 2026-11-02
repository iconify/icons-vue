<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snkfd_bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-side-fill-sharp" /></template>
<style>
.snkfd_bgo {
  fill: currentColor;
  d: path("M4.618 12h2.146l.894-.447l-2.105-4.211a2 2 0 0 1-.109-1.527a2 2 0 0 1 1.003-1.157l.461-.23a2 2 0 0 1 2.309.375l3.98 3.98l5.909-2.954A2 2 0 0 1 22 7.618v1.764a2 2 0 0 1-1.106 1.789L7.658 17.789c-.277.14-.583.212-.894.211H5.618a2 2 0 0 1-1.789-1.106l-1-2A2 2 0 0 1 4.618 12M21 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
