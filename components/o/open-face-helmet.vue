<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-9imdbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:open-face-helmet" /></template>
<style>
.b-9imdbim {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.358 7.049q-2.79 4.615-1.593 10.598q.012.063.036.124q.023.06.056.115t.075.104t.093.09q.049.041.106.073t.117.053t.124.033q.063.011.128.011h9.798q.231 1.74 1.588 2.679q1.67 1.156 3.893.267q.068-.027.13-.067t.115-.092t.094-.113q.042-.061.071-.129q.029-.067.045-.14q.015-.072.016-.146t-.013-.146q-.013-.073-.041-.142q-.027-.068-.067-.13t-.092-.115t-.113-.094q-.061-.042-.129-.071q-.067-.029-.14-.045q-.072-.015-.146-.016t-.146.013q-.073.013-.142.041q-1.474.589-2.482-.108q-.989-.685-.989-2.196v-6.25h5.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.436-2.345-5.78q-2.469-2.47-6.405-2.47q-5.24 0-8.142 4.799");
}

</style>
