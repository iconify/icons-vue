<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlr1o39qv.css';
import '../../css/c/cg7d2pfom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jlr1o39qv"/><circle class="cg7d2pfom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-contributions-ltr" /></template>
