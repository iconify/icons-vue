<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9sz3i9ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9sz3i9ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:regionalindicatorn" /></template>
