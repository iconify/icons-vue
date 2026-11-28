<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8_201bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8_201bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:skyscraper-search" /></template>
