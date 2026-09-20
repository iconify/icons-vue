<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6h32nivm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-cam-magnet-mount-sharp" /></template>
<style>
.t6h32nivm {
  fill: currentColor;
  d: path("M23 16.3q-.825 0-1.412-.587T21 14.3v-4q0-.85.588-1.425T23 8.3h1v8zm-10-5.025q0 1-.375 1.913t-1.1 1.637L7.25 19.1L.175 12.05l4.275-4.3q.725-.725 1.638-1.1T8 6.275q2.1 0 3.55 1.45t1.45 3.55m3.95 4.075L15.9 14.3l1.2-1.2H14v-1.5h3.2l-1.25-1.25L17 9.3l3 3z");
}

</style>
