<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1glu3bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1glu3bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pytorch" /></template>
