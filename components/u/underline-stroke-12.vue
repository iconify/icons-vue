<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uik-t4bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uik-t4bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:underline-stroke-12" /></template>
