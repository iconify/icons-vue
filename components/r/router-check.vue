<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn7800ahu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn7800ahu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:router-check" /></template>
