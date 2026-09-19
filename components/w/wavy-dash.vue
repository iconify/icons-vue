<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b83gw5wch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="b83gw5wch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:wavy-dash" /></template>
