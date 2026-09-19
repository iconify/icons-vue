<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2gz8uilm"/><path class="b-4-fre7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-calendar-view-month" /></template>
<style>
.b-4-fre7y {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M8 18H4v-5h4zm0-7H4V6h4zm6 7h-4v-5h4zm0-7h-4V6h4zm6 7h-4v-5h4zm0-7h-4V6h4z");
}

.y2gz8uilm {
  fill: currentColor;
  d: path("M4 6h4v5H4zm0 7h4v5H4zm6 0h4v5h-4zm6 0h4v5h-4zm0-7h4v5h-4zm-6 0h4v5h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
