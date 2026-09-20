<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msjkc3bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="msjkc3bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scratch-map-dark" /></template>
