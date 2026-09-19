<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2d2h3csf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="h2d2h3csf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pallet" /></template>
