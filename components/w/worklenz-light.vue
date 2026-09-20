<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9z0pybyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9z0pybyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:worklenz-light" /></template>
