<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tatiy3bwz.css';
import '../../css/o/oqknzwbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tatiy3bwz"/><path class="oqknzwbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pricing-container" /></template>
