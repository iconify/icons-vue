<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ritv8ybea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ritv8ybea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:monitor-warning-bold" /></template>
