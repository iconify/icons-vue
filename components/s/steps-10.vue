<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkhb168nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="fkhb168nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:steps-10" /></template>
