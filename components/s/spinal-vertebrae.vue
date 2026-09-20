<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3ee4zi2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m3ee4zi2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spinal-vertebrae" /></template>
