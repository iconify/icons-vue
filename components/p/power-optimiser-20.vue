<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h99zlyu1o.css';
import '../../css/r/rfb36bc4u.css';
import '../../css/f/fhp3j8bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h99zlyu1o"/><path class="rfb36bc4u"/><path class="fhp3j8bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-optimiser-20" /></template>
