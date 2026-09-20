<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxzwpsbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":150,"height":150};
const content = `<path class="gxzwpsbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nx-dark" /></template>
