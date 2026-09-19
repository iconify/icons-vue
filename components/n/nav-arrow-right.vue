<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs9ntbb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9ntbb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:nav-arrow-right" /></template>
