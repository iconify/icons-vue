<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra4ievf3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra4ievf3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mezmo" /></template>
