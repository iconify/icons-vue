<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5p28qgjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r5p28qgjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vector-square" /></template>
