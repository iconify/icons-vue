<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5knh5b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e5knh5b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:melon" /></template>
