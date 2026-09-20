<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohu3o4set.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohu3o4set"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:trainerroad" /></template>
