<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_yrg8bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_yrg8bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:save" /></template>
