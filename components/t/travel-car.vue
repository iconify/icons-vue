<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfi9q604p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rfi9q604p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:travel-car" /></template>
