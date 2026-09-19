<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjf09_bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yjf09_bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:trade-mark" /></template>
