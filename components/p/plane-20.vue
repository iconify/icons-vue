<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msk6w7bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="msk6w7bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plane-20" /></template>
