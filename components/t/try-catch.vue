<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3g_acbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b3g_acbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:try-catch" /></template>
