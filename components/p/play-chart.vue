<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrv6xysju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrv6xysju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play-chart" /></template>
