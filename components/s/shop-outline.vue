<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfu6ngbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfu6ngbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shop-outline" /></template>
