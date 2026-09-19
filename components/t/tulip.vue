<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_twobbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q_twobbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:tulip" /></template>
