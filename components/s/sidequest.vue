<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frkl9z0ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frkl9z0ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sidequest" /></template>
