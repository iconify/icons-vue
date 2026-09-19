<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px9_d10ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="px9_d10ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pill" /></template>
