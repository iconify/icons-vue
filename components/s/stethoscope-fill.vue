<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6o_i0g4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6o_i0g4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stethoscope-fill" /></template>
