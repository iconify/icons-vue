<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqydchbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqydchbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:select-off" /></template>
