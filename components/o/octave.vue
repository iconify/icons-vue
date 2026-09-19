<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjnocacyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hjnocacyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:octave" /></template>
