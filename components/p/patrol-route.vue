<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yajyc19qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:patrol-route" /></template>
<style>
.yajyc19qh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.97 14.03Q13.25 10.311 13.25 6q0-1.76 1.245-3.005T17.5 1.75t3.005 1.245T21.75 6q0 4.311-3.72 8.03q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094M7.431 18.7q2.027-.309 2.761-2.555q.945-2.895 3.308-2.895q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-1.275 0-1.882 1.861q-1.073 3.283-4.172 3.604q-.33 2.035-2.696 2.035Q2 22.25 2 19.5t2.75-2.75q2.316 0 2.681 1.95");
}

</style>
