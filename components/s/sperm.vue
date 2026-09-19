<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orbb9dbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="orbb9dbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sperm" /></template>
