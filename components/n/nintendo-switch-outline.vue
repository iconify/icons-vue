<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8lpo2d8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n8lpo2d8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:nintendo-switch-outline" /></template>
