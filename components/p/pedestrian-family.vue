<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj21nobix.css';
import '../../css/l/lt2ak2b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aj21nobix"/><path class="lt2ak2b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pedestrian-family" /></template>
