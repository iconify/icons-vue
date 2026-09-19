<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_-3zpb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_-3zpb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:warning-circled-outline" /></template>
