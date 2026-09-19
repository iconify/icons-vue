<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz3r-qb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rz3r-qb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:swap-horizontal" /></template>
