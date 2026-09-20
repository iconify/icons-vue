<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhua32s8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lhua32s8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:move-first-ltr" /></template>
