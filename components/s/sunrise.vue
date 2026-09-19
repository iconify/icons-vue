<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr1ixoqzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mr1ixoqzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sunrise" /></template>
