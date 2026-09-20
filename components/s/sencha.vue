<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt91c6wab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lt91c6wab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:sencha" /></template>
