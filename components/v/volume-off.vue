<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udpa8y6px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udpa8y6px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:volume-off" /></template>
