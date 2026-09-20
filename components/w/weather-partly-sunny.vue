<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lamduibsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lamduibsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:weather-partly-sunny" /></template>
