<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku5kwhbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":1024};
const content = `<path class="ku5kwhbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:voltage" /></template>
