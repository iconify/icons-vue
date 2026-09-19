<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2r-xbbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z2r-xbbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:red-apple" /></template>
