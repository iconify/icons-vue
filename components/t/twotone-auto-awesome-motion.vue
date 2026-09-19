<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhrdhzkhf"/><path class="kzxp7mbaf"/><path class="gus7y2-gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-auto-awesome-motion" /></template>
<style>
.bhrdhzkhf {
  fill: currentColor;
  d: path("M12 12h8v8h-8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.gus7y2-gr {
  fill: currentColor;
  d: path("M18 6H8c-1.1 0-2 .9-2 2v10h2V8h10z");
}

.kzxp7mbaf {
  fill: currentColor;
  d: path("M14 2H4c-1.1 0-2 .9-2 2v10h2V4h10zm6 8h-8c-1.1 0-2 .9-2 2v8c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-8c0-1.1-.9-2-2-2m0 10h-8v-8h8z");
}

</style>
