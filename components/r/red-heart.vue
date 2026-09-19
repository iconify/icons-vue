<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri_-vhbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ri_-vhbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:red-heart" /></template>
