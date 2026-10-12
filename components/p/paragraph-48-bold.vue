<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4_y_kbip.css';
import '../../css/q/qpe8ekbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f4_y_kbip"/><path class="qpe8ekbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paragraph-48-bold" /></template>
