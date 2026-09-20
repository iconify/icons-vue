<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9y17ccuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9y17ccuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pluton-dark" /></template>
