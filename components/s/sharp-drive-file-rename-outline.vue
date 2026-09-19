<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1pdedcym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-drive-file-rename-outline" /></template>
<style>
.y1pdedcym {
  fill: currentColor;
  d: path("m15 16l-4 4h10v-4zm-2.94-8.81L3 16.25V20h3.75l9.06-9.06zm1.072-1.067l2.539-2.539l3.747 3.748L16.88 9.87z");
}

</style>
