<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2djj2bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="z2djj2bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:swap-vertical-circle" /></template>
