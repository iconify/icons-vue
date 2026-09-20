<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns0ymobwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ns0ymobwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:philpapers-square" /></template>
