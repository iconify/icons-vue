<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1_601ryt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:privacy" /></template>
<style>
.d1_601ryt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.258 2.046l7.5 2.75q.108.04.2.11q.091.07.157.165q.066.094.1.204q.035.11.035.225v6q0 7.276-7.973 10.447Q12.144 22 12 22t-.277-.053Q3.75 18.776 3.75 11.5v-6q0-.115.035-.225q.034-.11.1-.204q.066-.095.157-.165q.092-.07.2-.11l7.5-2.75Q11.867 2 12 2t.258.046M12 7.75q-2.75 0-2.75 2.75q0 2.345 2 2.69v2.31q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.31q2-.345 2-2.69q0-2.75-2.75-2.75");
}

</style>
