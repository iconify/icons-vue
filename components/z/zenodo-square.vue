<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nepf93bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nepf93bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:zenodo-square" /></template>
