<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2o51bbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="j2o51bbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sd-card" /></template>
