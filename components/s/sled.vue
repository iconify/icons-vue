<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj26e4bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oj26e4bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sled" /></template>
