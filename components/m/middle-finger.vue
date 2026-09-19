<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlest2i5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rlest2i5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:middle-finger" /></template>
