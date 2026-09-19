<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4zbtcbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x4zbtcbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-bald" /></template>
