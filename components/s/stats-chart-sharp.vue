<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvfduderi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvfduderi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:stats-chart-sharp" /></template>
