<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_7jr_bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y_7jr_bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:poe" /></template>
