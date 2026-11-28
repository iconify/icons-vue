<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfb_8bcez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfb_8bcez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:plane-arrow-down" /></template>
