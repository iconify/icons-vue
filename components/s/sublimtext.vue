<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlyur0l4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mlyur0l4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sublimtext" /></template>
