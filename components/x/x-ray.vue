<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sflgbubsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sflgbubsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:x-ray" /></template>
