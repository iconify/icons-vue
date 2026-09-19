<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyumgc4hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pyumgc4hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:trophy" /></template>
