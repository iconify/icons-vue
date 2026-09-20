<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs-7npbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zs-7npbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-folia-dark" /></template>
