<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4ww4zb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n4ww4zb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:red-triangle" /></template>
