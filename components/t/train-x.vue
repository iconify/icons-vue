<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd3fyqbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd3fyqbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:train-x" /></template>
