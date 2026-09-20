<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynpe42bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ynpe42bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:street-road" /></template>
