<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wb7_65b-g.css';
import '../../css/v/vkdts-b4s.css';
import '../../css/l/lzvosfbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wb7_65b-g"/><path class="vkdts-b4s"/><path class="lzvosfbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:setting-done-04" /></template>
