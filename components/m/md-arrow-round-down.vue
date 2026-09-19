<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmsij2f1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pmsij2f1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-arrow-round-down" /></template>
