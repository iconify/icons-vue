<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccm_eobhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ccm_eobhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:show-sidebar" /></template>
