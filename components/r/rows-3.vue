<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5q7f7bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5q7f7bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rows-3" /></template>
