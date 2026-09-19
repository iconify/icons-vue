<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxs16d34a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zxs16d34a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:teacup-without-handle" /></template>
