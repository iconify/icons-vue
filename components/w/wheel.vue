<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p52rodbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p52rodbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:wheel" /></template>
