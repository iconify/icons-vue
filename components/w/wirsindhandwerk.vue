<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck1m0fbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ck1m0fbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:wirsindhandwerk" /></template>
