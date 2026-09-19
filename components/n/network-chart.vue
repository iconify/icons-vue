<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhxa97bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhxa97bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:network-chart" /></template>
