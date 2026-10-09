<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo10pr4qb.css';
import '../../css/j/j3e_0zbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uo10pr4qb"/><path class="j3e_0zbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunny-intervals-20-bold" /></template>
