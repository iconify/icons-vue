<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_4kopb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v_4kopb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sari" /></template>
