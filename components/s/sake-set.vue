<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq8kx1wob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sake-set" /></template>
<style>
.gq8kx1wob {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 2.25h-3q-.053 0-.106.008q-.073.01-.143.034q-.07.025-.133.063q-.064.037-.119.087T5.9 2.55q-.044.059-.076.126q-.032.066-.051.138q-.018.071-.022.145t.007.147l.422 2.956Q2.25 8.162 2.25 15v4.5q0 2.25 2.25 2.25h7q2.25 0 2.25-2.25V15q0-6.838-3.93-8.938l.422-2.956q.008-.053.008-.106q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q9.574 2.25 9.5 2.25m6.5 12h5.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.015.147l-.986 4.932Q21.21 21.75 19.5 21.75H18q-1.71 0-1.749-1.671l-.986-4.932q-.015-.072-.015-.146t.014-.147q.015-.072.043-.14t.069-.13t.093-.114t.114-.093q.061-.041.129-.07q.068-.028.141-.042T16 14.25");
}

</style>
