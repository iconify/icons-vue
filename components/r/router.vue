<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn4j-ibjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn4j-ibjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:router" /></template>
