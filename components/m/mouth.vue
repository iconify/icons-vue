<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfsc4vbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yfsc4vbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:mouth" /></template>
