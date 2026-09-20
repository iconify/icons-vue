<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc17hactt.css';
import '../../css/b/bo_dldbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yc17hactt"/><path class="bo_dldbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-umbrella-snowing" /></template>
