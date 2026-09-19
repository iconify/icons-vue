<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey6g4lbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ey6g4lbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:oncoming-automobile" /></template>
