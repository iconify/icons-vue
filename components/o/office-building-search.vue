<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyc0uprxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyc0uprxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:office-building-search" /></template>
