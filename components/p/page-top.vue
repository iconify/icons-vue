<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckn_6fogz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ckn_6fogz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:page-top" /></template>
