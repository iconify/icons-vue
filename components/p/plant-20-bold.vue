<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbo2x6civ.css';
import '../../css/a/a-b9sjb0f.css';
import '../../css/r/roiba_3fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jbo2x6civ"/><path class="a-b9sjb0f"/><path class="roiba_3fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plant-20-bold" /></template>
