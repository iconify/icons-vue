<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjo68qbsq.css';
import '../../css/u/uhso3bbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zjo68qbsq"/><path class="uhso3bbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-filled" /></template>
