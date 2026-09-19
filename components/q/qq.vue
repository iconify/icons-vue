<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n24_ilbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n24_ilbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:qq" /></template>
