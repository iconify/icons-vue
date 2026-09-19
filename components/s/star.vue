<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aouu4gbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="aouu4gbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:star" /></template>
