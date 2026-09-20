<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu4l0sb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu4l0sb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-bottom-inactive" /></template>
