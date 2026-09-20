<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udv3tkbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="udv3tkbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:up-outline" /></template>
