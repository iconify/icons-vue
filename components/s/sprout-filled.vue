<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ros-colzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ros-colzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sprout-filled" /></template>
