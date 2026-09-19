<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_6l8gk2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j_6l8gk2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sun-behind-large-cloud" /></template>
