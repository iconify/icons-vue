<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgnx6ab5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgnx6ab5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:paint" /></template>
