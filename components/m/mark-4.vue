<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feklsmb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="feklsmb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:mark-4" /></template>
