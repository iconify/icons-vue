<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t8ru5zfjb.css';
import '../../css/s/sbi675a4a.css';
import '../../css/o/o4c4ve50q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t8ru5zfjb"/><path class="sbi675a4a"/><path class="o4c4ve50q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:speed-train-02" /></template>
