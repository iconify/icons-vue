<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k56bsdz-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="k56bsdz-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:pin" /></template>
