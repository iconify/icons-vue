<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0z0rdxri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y0z0rdxri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:smartwatch" /></template>
