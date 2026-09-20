<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0nqa7byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t0nqa7byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-map-pin" /></template>
