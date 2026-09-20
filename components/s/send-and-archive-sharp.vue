<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px_qr1bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:send-and-archive-sharp" /></template>
<style>
.px_qr1bex {
  fill: currentColor;
  d: path("M4.192 18.539v-5.193L10.04 12l-5.847-1.346v-5.27l12.281 5.25h-.07q-2.116.174-3.702 1.553t-1.778 3.46zm9.78.912q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165t-2.836-1.165m2.836-.047l2.73-2.731l-.546-.546l-1.8 1.8v-4.1h-.769v4.1l-1.8-1.8l-.546.546z");
}

</style>
