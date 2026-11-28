<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl-n21a0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl-n21a0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smart-home-plus" /></template>
