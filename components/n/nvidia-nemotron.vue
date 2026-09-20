<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp6lvlbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp6lvlbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nvidia-nemotron" /></template>
