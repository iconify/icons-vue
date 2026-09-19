<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcrbt8b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xcrbt8b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:visual-studio" /></template>
