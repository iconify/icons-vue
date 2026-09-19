<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st7_mloem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="st7_mloem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:passport" /></template>
