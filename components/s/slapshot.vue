<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5-sqnbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:slapshot" /></template>
<style>
.s5-sqnbsc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.18 17.817l7-15q.031-.067.048-.139q.018-.071.021-.145t-.008-.147t-.036-.142t-.064-.133t-.088-.118t-.109-.098q-.06-.043-.127-.075q-.135-.063-.284-.069t-.289.044t-.251.152t-.173.236L9.022 16.75H4.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069q.068.028.141.043t.146.014h5q.107 0 .21-.03t.193-.087q.09-.058.161-.138q.07-.081.116-.178m3.07.183q0-2.75 4.25-2.75T21.75 18t-4.25 2.75T13.25 18");
}

</style>
