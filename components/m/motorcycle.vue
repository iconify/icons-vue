<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzisbh2dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lzisbh2dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:motorcycle" /></template>
