<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3rebkngr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3rebkngr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:tech-stories" /></template>
