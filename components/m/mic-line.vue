<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7578qc1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7578qc1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-line" /></template>
