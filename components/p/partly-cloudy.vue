<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7v3c9hfx.css';
import '../../css/j/jaeag7yzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h7v3c9hfx"/><path class="jaeag7yzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:partly-cloudy" /></template>
