<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f90z9pbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-nail" /></template>
<style>
.f90z9pbmu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q2.75 0 2.75 2.75v4q0 .846-.26 1.432q.124.107.192.256q.068.148.068.312v.867q5 .987 5 5.633v2q0 3.25-3.25 3.25h-9q-1.346 0-2.298-.952T4.25 19v-2q0-4.646 5-5.633V10.5q0-.164.068-.312q.068-.149.192-.256q-.26-.586-.26-1.432v-4q0-2.75 2.75-2.75m-3.25 16.5V16q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T8 15.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.25 16v2.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T8 19t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
