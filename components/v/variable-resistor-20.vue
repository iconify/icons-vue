<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd76n1f0v.css';
import '../../css/f/flk8b6but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gd76n1f0v"/><path class="flk8b6but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:variable-resistor-20" /></template>
