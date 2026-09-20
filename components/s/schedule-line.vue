<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa_8_q4im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa_8_q4im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:schedule-line" /></template>
