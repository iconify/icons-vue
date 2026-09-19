<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml2slab6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ml2slab6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:pointer" /></template>
