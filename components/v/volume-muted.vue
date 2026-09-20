<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khjpa1jsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="khjpa1jsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:volume-muted" /></template>
