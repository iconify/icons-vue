<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enyhqqbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enyhqqbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:search1api" /></template>
