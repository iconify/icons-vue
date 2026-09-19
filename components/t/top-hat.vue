<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuhafbtkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yuhafbtkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:top-hat" /></template>
