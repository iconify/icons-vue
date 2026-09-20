<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb18fn7er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mb18fn7er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-giving-dark" /></template>
