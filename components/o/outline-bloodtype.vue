<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c38xzzb2u"/><path class="kq_3pj0iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-bloodtype" /></template>
<style>
.c38xzzb2u {
  fill: currentColor;
  d: path("M9 16h6v2H9zm4-7h-2v2H9v2h2v2h2v-2h2v-2h-2z");
}

.kq_3pj0iw {
  fill: currentColor;
  d: path("M12 2c-5.33 4.55-8 8.48-8 11.8c0 4.98 3.8 8.2 8 8.2s8-3.22 8-8.2c0-3.32-2.67-7.25-8-11.8m0 18c-3.35 0-6-2.57-6-6.2c0-2.34 1.95-5.44 6-9.14c4.05 3.7 6 6.79 6 9.14c0 3.63-2.65 6.2-6 6.2");
}

</style>
