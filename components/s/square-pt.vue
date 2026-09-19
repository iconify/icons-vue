<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8450_zvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m8450_zvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:square-pt" /></template>
