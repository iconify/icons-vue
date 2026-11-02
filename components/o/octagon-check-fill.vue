<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f565zjk_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-check-fill" /></template>
<style>
.f565zjk_l {
  fill: currentColor;
  d: path("M12 2h3c1.039 0 1.992.578 2.707 1.293l3 3C21.422 7.008 22 7.961 22 9v6c0 1.039-.578 1.992-1.293 2.707l-3 3C16.992 21.422 16.039 22 15 22H9c-1.039 0-1.992-.578-2.707-1.293l-3-3C2.578 16.992 2 16.039 2 15V9c0-1.039.578-1.992 1.293-2.707l3-3C7.008 2.578 7.961 2 9 2Zm-1.067 11.519l-2.226-2.226a.999.999 0 1 0-1.414 1.414l3 3a1 1 0 0 0 1.475-.067l5-6a1 1 0 1 0-1.536-1.28Z");
}

</style>
