<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffzgqjqfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ffzgqjqfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-sleet-storm" /></template>
