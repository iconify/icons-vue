<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aju4stb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="aju4stb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:platform" /></template>
