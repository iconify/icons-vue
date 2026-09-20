<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aotledc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-secure-alarm-sharp" /></template>
<style>
.aotledc4i {
  fill: currentColor;
  d: path("M8.493 20.292q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708M8.231 9.769h1.538V8.231H8.231zm3 0h1.538V8.231h-1.538zm3 0h1.538V8.231h-1.538zm-6 3h1.538v-1.538H8.231zm3 0h1.538v-1.538h-1.538zm3 0h1.538v-1.538h-1.538zm-6 3h1.538v-1.538H8.231zm3 0h1.538v-1.538h-1.538zm3 0h1.538v-1.538h-1.538z");
}

</style>
