<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4b2hccvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a4b2hccvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:water-pistol" /></template>
