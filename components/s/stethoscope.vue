<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbzv8sbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1536};
const content = `<path class="vbzv8sbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:stethoscope" /></template>
