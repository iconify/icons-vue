<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy5c86bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy5c86bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:saudia" /></template>
