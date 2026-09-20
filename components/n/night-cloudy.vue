<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4r25c7hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="m4r25c7hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-cloudy" /></template>
