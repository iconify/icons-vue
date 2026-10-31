<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr47fgb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr47fgb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-fill-round" /></template>
