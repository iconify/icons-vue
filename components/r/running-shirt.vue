<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt_nuk8ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rt_nuk8ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:running-shirt" /></template>
