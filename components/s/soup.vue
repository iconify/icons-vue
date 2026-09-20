<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-6k85rjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w-6k85rjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:soup" /></template>
