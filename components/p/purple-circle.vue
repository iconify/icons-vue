<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/staci0wam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="staci0wam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:purple-circle" /></template>
