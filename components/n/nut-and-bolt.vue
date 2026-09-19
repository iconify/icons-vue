<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v28j06bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v28j06bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:nut-and-bolt" /></template>
