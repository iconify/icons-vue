<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czwmjhe3n.css';
import '../../css/y/yv8w4bckf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="czwmjhe3n"/><path class="yv8w4bckf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:navaid-tacan" /></template>
