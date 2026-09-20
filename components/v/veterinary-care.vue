<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxolw7z3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="cxolw7z3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:veterinary-care" /></template>
