<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw0z-bnbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw0z-bnbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:plus-hexagon" /></template>
