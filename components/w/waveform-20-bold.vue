<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z89_jubnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z89_jubnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waveform-20-bold" /></template>
