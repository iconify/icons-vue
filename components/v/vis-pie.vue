<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg4agoyds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jg4agoyds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-pie" /></template>
