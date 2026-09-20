<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd0bgsbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wd0bgsbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pie-chart-fill" /></template>
