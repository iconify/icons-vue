<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnmickb1m"/><path class="cm22sob3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-electrical-services" /></template>
<style>
.cm22sob3h {
  fill: currentColor;
  d: path("M4 5c0 .55.45 1 1 1h3.5c.83 0 1.5.67 1.5 1.5S9.33 9 8.5 9H7c-2.21 0-4 1.79-4 4s1.79 4 4 4h2v-2H7c-1.1 0-2-.9-2-2s.9-2 2-2h1.5c1.93 0 3.5-1.57 3.5-3.5S10.43 4 8.5 4H5c-.55 0-1 .45-1 1");
}

.mnmickb1m {
  fill: currentColor;
  d: path("M20 15h-2v-2h2c.55 0 1 .45 1 1s-.45 1-1 1m0 4h-2v-2h2c.55 0 1 .45 1 1s-.45 1-1 1m-6-7c-1.1 0-2 .9-2 2h-2v4h2c0 1.1.9 2 2 2h3v-8z");
}

</style>
