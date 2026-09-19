<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdtz0m5lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zdtz0m5lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:poo-storm" /></template>
