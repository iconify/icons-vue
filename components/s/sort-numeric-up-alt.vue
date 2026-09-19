<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyser73hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xyser73hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-numeric-up-alt" /></template>
