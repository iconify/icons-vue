<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y84wcytgu"/><path class="opeuxkblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-store-mall-directory" /></template>
<style>
.opeuxkblj {
  fill: currentColor;
  d: path("m4 7l-1 5v2h1v6h10v-6h4v6h2v-6h1v-2l-1-5zm8 11H6v-4h6zm-6.96-6l.6-3h12.72l.6 3zM4 4h16v2H4z");
}

.y84wcytgu {
  fill: currentColor;
  d: path("m5.64 9l-.6 3h13.92l-.6-3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
