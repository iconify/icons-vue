<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2ygjsqjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="m2ygjsqjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:upload" /></template>
