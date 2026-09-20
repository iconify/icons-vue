<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x565jhkyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x565jhkyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:scopus-square" /></template>
