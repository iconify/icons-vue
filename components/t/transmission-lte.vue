<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvmivbb5a.css';
import '../../css/i/ih5xe3bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cvmivbb5a"/><path class="ih5xe3bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:transmission-lte" /></template>
