<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0epiybna.css';
import '../../css/f/f_x7syode.css';
import '../../css/h/hacaudf9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o0epiybna"/><path class="f_x7syode"/><path class="hacaudf9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:virtual-power-plant-20-bold" /></template>
