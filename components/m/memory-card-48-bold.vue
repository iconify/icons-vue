<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmodlobup.css';
import '../../css/e/emd0dl2-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hmodlobup"/><path class="emd0dl2-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:memory-card-48-bold" /></template>
