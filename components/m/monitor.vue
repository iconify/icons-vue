<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/romo1bcpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="romo1bcpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:monitor" /></template>
