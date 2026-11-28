<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4xs89buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4xs89buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:watering-can-clock" /></template>
