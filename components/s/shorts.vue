<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe2begbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xe2begbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:shorts" /></template>
