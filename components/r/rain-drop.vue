<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdk57la4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rain-drop" /></template>
<style>
.hdk57la4f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.506 1.936q-.038.032-.07.07Q4.25 10.218 4.25 15q0 3.21 2.27 5.48T12 22.75t5.48-2.27T19.75 15q0-4.782-7.186-12.994q-.098-.112-.232-.178q-.133-.066-.282-.076t-.29.038q-.142.047-.254.146M12 18.25q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-1.76 0-3.005-1.245T7.75 15.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2.75 2.75 2.75");
}

</style>
