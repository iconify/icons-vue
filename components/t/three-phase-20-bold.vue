<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iicur4vle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iicur4vle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:three-phase-20-bold" /></template>
