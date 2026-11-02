<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chu61h8mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:outdent-fill-sharp" /></template>
<style>
.chu61h8mr {
  fill: currentColor;
  d: path("M12 5h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2M8.707 8.707L5.414 12l3.293 3.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414M12 9h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2m0 4h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2m0 4h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
