<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f51_hbcsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f51_hbcsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trapezoid-20" /></template>
