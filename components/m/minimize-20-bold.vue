<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj9pw9bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qj9pw9bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minimize-20-bold" /></template>
