<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkfmv4bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkfmv4bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:weightlifting-line" /></template>
