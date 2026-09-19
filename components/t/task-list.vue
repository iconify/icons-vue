<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us6p5c7zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us6p5c7zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:task-list" /></template>
