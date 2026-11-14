<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bknnv0bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pipeline-coverage" /></template>
<style>
.bknnv0bzx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 3.75h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-3.25 3.5h.25q1.036 0 1.768.732T21 9.75v9.5q0 1.036-.732 1.768t-1.768.732h-.25q-1.036 0-1.768-.732t-.732-1.768v-9.5q0-2.5 2.5-2.5M12 10.75h-.25q-2.5 0-2.5 2.5v6q0 1.036.732 1.768t1.768.732H12q1.036 0 1.768-.732t.732-1.768v-6q0-1.036-.732-1.768T12 10.75m-6.75 3.5h.25q1.036 0 1.768.732T8 16.75v2.5q0 1.036-.732 1.768T5.5 21.75h-.25q-1.036 0-1.768-.732T2.75 19.25v-2.5q0-2.5 2.5-2.5");
}

</style>
