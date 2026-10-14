<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trkm4uhtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":32};
const content = `<path class="trkm4uhtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sigma-computing" /></template>
