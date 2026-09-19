<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn6mf84ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zn6mf84ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-stroke-12" /></template>
