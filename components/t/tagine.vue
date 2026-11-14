<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqt94_twl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tagine" /></template>
<style>
.dqt94_twl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 3.25q0-2 2-2t2 2q0 .702-.246 1.157q2.181 7.552 5.95 9.843H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 5.25-9.75 5.25T2.25 15q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 14.25h1.296q3.769-2.291 5.95-9.843Q10 3.952 10 3.25m2 2h-.438q-1.845 6.137-4.833 9h10.542q-2.988-2.863-4.833-9z");
}

</style>
