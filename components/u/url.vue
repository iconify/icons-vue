<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8jnt9tue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q8jnt9tue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:url" /></template>
