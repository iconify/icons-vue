<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vld8rjbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vld8rjbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:musical-keyboard" /></template>
