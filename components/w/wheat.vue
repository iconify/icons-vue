<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy5we8etf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uy5we8etf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wheat" /></template>
