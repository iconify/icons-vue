<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2idfnbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2idfnbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:pie-chart" /></template>
