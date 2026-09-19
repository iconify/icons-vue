<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-wwcb8-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y-wwcb8-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:police-car-light" /></template>
