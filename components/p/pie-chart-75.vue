<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twdnls6-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twdnls6-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:pie-chart-75" /></template>
