<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy-s0bbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="iy-s0bbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:search" /></template>
