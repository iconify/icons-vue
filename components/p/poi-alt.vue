<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oit-hng_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="oit-hng_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:poi-alt" /></template>
