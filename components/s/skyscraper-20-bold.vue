<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrwbit1kg.css';
import '../../css/l/l_fhzdbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vrwbit1kg"/><path class="l_fhzdbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skyscraper-20-bold" /></template>
