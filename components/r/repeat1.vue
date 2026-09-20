<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgupwhzsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vgupwhzsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:repeat1" /></template>
