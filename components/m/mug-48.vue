<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4kijcj5b.css';
import '../../css/t/tea15-vcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d4kijcj5b"/><path class="tea15-vcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mug-48" /></template>
