<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9v157lcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9v157lcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:maps-arrow-diagonal" /></template>
