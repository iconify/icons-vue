<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub6fx6bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ub6fx6bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openziti-dark" /></template>
