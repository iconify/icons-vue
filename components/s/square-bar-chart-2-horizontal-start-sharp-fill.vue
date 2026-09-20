<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imtohwlhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="imtohwlhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-2-horizontal-start-sharp-fill" /></template>
