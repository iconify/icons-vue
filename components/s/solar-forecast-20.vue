<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emwyceb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="emwyceb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-forecast-20" /></template>
