<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6hkjmaim.css';
import '../../css/j/j9quaibxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6hkjmaim"/><path class="j9quaibxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spillway-20-bold" /></template>
