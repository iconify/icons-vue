<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qwntkab6t.css';
import '../../css/i/in9uiwghv.css';
import '../../css/t/tfmz6fzjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qwntkab6t"/><path class="in9uiwghv"/><path class="tfmz6fzjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:umbrella-dollar" /></template>
