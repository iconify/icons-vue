<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4xw6ab6k.css';
import '../../css/x/xvdg5pbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4xw6ab6k"/><path class="xvdg5pbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:train-48" /></template>
