<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzh6otbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uzh6otbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sun-behind-rain-cloud" /></template>
