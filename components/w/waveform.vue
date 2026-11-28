<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw9dhccbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw9dhccbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:waveform" /></template>
