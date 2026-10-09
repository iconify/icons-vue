<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vufao1btt.css';
import '../../css/q/q59a9ubij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vufao1btt"/><path class="q59a9ubij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-thermal-20" /></template>
