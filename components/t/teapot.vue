<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxi3c60rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vxi3c60rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:teapot" /></template>
