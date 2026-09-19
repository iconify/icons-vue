<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bql_2u4-a.css';
import '../../css/u/uwprsn25p.css';
import '../../css/d/d8sy1ipse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bql_2u4-a"/><path class="uwprsn25p"/><path class="d8sy1ipse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:time-quarter" /></template>
