<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/addq5hbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="addq5hbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:small-blue-diamond" /></template>
