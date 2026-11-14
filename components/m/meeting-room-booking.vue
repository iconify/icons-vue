<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9pfw8bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:meeting-room-booking" /></template>
<style>
.o9pfw8bar {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.5q-4 0-4 4t4 4t4-4q0-1.657-1.172-2.828Q13.657 1.5 12 1.5M3.25 13.75q0-3 8.75-3t8.75 3q0 2.869-8 2.994v3.506H15q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 20.25h2.25v-3.506q-8-.125-8-2.994");
}

</style>
