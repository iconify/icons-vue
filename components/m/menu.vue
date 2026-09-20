<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zssm2xbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zssm2xbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:menu" /></template>
