<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uissoqbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uissoqbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-under-taxi-checkerboard" /></template>
