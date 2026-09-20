<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4--32bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="k4--32bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:telescope" /></template>
