<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd8p0tzdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wd8p0tzdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:numerical-sorting-12" /></template>
