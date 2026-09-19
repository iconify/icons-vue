<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4_hapb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="q4_hapb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:passport" /></template>
