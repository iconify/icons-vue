<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jppv-o5ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="jppv-o5ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:ticket" /></template>
