<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laukk-9tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="laukk-9tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shapes" /></template>
