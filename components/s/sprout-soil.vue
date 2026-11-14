<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf1wbpror"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sprout-soil" /></template>
<style>
.rf1wbpror {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.927 8.254q.451-.977 1.202-1.817Q15.086 4.25 18 4.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2.963-1.879 5.063q-1.699 1.899-4.121 2.149v2.673q6.642.183 9.342 3.655q.045.058.078.124q.034.066.053.137q.02.071.025.145t-.004.147t-.032.143q-.024.071-.06.135q-.037.064-.085.12t-.107.101q-.098.077-.217.117q-.118.041-.243.041h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 19q0-.125.041-.243q.04-.119.117-.217q2.7-3.472 9.342-3.655V9q0-.069.013-.137t.037-.133t.062-.124q.036-.059.082-.11t.102-.093t.117-.073t.129-.05q.066-.02.135-.026");
}

</style>
