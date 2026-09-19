<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjp6_9bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kjp6_9bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:task-solid" /></template>
