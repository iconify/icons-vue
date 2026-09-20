<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mset3p40f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mset3p40f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spectrum" /></template>
