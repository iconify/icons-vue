<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zymyolbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zymyolbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:paint-brush" /></template>
