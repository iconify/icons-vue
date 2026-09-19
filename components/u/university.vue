<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey-koukvr.css';
import '../../css/n/n11wxrbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ey-koukvr"/><path class="n11wxrbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:university" /></template>
