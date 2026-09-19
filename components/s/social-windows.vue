<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq5hysa4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="uq5hysa4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-windows" /></template>
