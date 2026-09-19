<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeedibbap.css';
import '../../css/q/qzrf2_c2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aeedibbap"/><path class="qzrf2_c2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:spiral-notepad" /></template>
