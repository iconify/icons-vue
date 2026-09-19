<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exqw53b-w.css';
import '../../css/v/v2qi5lg1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="exqw53b-w"/><path class="v2qi5lg1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:timer" /></template>
