<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpg_28bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mpg_28bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:waze-light" /></template>
