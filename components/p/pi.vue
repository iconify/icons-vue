<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyu5frbjg.css';
import '../../css/z/zt0uakzko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800};
const content = `<path class="vyu5frbjg"/><path class="zt0uakzko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pi" /></template>
