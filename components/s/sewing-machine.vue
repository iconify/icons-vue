<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nok8b0muj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="nok8b0muj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:sewing-machine" /></template>
