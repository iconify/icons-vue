<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euvm4m4yy.css';
import '../../css/d/d7eb7bjvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer euvm4m4yy"/><path class="d7eb7bjvg duoicon-primary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:smartphone" /></template>
