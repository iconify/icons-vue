<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex7vb15ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ex7vb15ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waveform-20" /></template>
