<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twx7oyadf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="twx7oyadf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:stethoscope" /></template>
