<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibm1vrbdc.css';
import '../../css/k/k_93etbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ibm1vrbdc"/><path class="k_93etbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plunger-20-bold" /></template>
