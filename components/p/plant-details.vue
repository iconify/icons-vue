<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn0sz_55w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yn0sz_55w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-details" /></template>
