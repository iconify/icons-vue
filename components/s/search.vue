<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0b0pkckb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d0b0pkckb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:search" /></template>
