<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv_1nabsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rv_1nabsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:tshirt" /></template>
