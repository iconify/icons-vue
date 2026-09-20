<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_95w9bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_95w9bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ziggo" /></template>
