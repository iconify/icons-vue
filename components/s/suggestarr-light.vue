<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-3_x9pzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-3_x9pzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:suggestarr-light" /></template>
