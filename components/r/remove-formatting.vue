<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlmudxbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlmudxbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:remove-formatting" /></template>
