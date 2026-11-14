<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fskwnibct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tankless-water-heater" /></template>
<style>
.fskwnibct {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 5V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V5H9Q7.24 5 5.995 6.245T4.75 9.25v9q0 1.76 1.245 3.005T9 22.5h6q1.76 0 3.005-1.245t1.245-3.005v-9q0-1.76-1.245-3.005T15 5zm0 3.75q0 .867 1.626 2.387q2.374 2.219 2.374 4.113q0 1.968-1.391 3.359T12 20t-3.359-1.391T7.25 15.25q0-2.964 2.415-4.171q.063-.032.132-.051t.14-.025t.142.001t.139.029q.069.02.132.054q.063.033.119.078q.056.044.102.099q.046.054.081.116q.02-1.99.724-3.046q.041-.061.093-.114q.052-.052.114-.093q.061-.041.129-.07q.068-.028.141-.042T11.999 8t.147.014q.072.015.14.043t.13.069q.077.051.139.12q.063.068.106.15q.044.082.066.172t.023.182");
}

</style>
