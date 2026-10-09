<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m230b2b0n.css';
import '../../css/p/pg9gpuirh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m230b2b0n"/><path class="pg9gpuirh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sofa-48" /></template>
