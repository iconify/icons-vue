<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiyqsjbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="fiyqsjbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:puzzle-piece" /></template>
