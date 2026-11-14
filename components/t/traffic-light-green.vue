<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m86cx_bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:traffic-light-green" /></template>
<style>
.m86cx_bcw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.625 1.25h.75q2.123 0 3.624 1.501T17.5 6.375v9.25q0 2.123-1.501 3.624q-1.367 1.367-3.249 1.489V22q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 22v-1.262q-1.882-.122-3.249-1.489Q6.5 17.748 6.5 15.625v-9.25q0-2.123 1.501-3.624t3.624-1.501M9.5 5.75q0 2.5 2.5 2.5q1.036 0 1.768-.732T14.5 5.75t-.732-1.768T12 3.25q-2.5 0-2.5 2.5M12 8.5q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T14.5 11t-.732-1.768T12 8.5m-2.5 7.75q0 2.5 2.5 2.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768T12 13.75q-2.5 0-2.5 2.5");
}

</style>
