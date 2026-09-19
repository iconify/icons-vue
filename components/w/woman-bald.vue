<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g87_e866g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g87_e866g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:woman-bald" /></template>
