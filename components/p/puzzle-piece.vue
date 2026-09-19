<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5u0jjb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n5u0jjb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:puzzle-piece" /></template>
