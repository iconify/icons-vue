<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctmyokx8x.css';
import '../../css/j/j_as-15we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ctmyokx8x"/><path class="j_as-15we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-20-bold" /></template>
