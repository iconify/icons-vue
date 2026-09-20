<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa6r-zkqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa6r-zkqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tuxedo-computers" /></template>
