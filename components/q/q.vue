<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcy5x_18o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fcy5x_18o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:q" /></template>
