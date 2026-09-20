<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6mr8zbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x6mr8zbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:water-sunbathing" /></template>
