<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rah4qbcvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rah4qbcvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-flag" /></template>
