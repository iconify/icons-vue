<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0km01bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="m0km01bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-cloudy-windy" /></template>
