<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1b3dq-3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:piste-easy" /></template>
<style>
.o1b3dq-3k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 8q0-2.589 1.831-4.419Q9.411 1.75 12 1.75t4.419 1.831T18.25 8t-1.831 4.419q-1.559 1.56-3.669 1.791v6.54H15q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 20.75h2.25v-6.54q-2.11-.231-3.669-1.791Q5.75 10.589 5.75 8");
}

</style>
