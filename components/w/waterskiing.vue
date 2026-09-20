<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou09uufas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ou09uufas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:waterskiing" /></template>
