<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3fnezkjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="l3fnezkjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:text-width" /></template>
