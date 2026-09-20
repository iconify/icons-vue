<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo1p5vwpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo1p5vwpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:pause-square-fill" /></template>
