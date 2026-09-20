<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/ten2dqbwx.css';
import '../../css/o/oockgugaw.css';
import '../../css/a/axjtsp52f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ten2dqbwx"/><path class="oockgugaw"/><path class="axjtsp52f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-horizontal-broken" /></template>
