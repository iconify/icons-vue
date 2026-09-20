<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-8ia3bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-8ia3bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:merge-cells-horizontal" /></template>
