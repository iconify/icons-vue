<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um_xhab5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="um_xhab5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:martial-arts-uniform" /></template>
