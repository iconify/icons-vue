<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lou2zl3dr.css';
import '../../css/p/p3_4el9va.css';
import '../../css/m/mc35szfhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lou2zl3dr"/><path class="p3_4el9va"/><path class="mc35szfhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-academic-cap-broken" /></template>
