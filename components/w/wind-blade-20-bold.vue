<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onndsh4cj.css';
import '../../css/d/du94n1byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="onndsh4cj"/><path class="du94n1byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-blade-20-bold" /></template>
