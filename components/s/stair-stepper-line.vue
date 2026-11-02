<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoh6psbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoh6psbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stair-stepper-line" /></template>
