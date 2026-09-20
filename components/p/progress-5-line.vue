<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccw2tfb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccw2tfb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-5-line" /></template>
