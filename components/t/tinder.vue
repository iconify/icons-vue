<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjm2rybfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjm2rybfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tinder" /></template>
