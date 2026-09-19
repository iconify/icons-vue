<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6v_4mx_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h6v_4mx_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:tomato" /></template>
