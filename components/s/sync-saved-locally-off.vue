<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt040wc1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sync-saved-locally-off" /></template>
<style>
.vt040wc1h {
  fill: currentColor;
  d: path("m21.192 22.608l-3.146-3.146H1.77v-1h15.272l-1-1H4.616q-.691 0-1.153-.463T3 15.846V6.042q0-.327.173-.586q.173-.26.442-.414L1.392 2.808L2.1 2.1l19.8 19.8zm-1.069-5.335L13.79 10.94l2.099-2.078l-.714-.714l-2.079 2.079l-5.784-5.765h12.073q.69 0 1.153.462T21 6.077v9.77q0 .419-.209.81q-.208.391-.668.616");
}

</style>
