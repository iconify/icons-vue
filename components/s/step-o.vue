<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyoqdrbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cyoqdrbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:step-o" /></template>
