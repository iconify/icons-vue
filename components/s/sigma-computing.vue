<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es1ac2bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":32};
const content = `<path class="es1ac2bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sigma-computing" /></template>
