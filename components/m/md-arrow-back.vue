<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx6re6bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gx6re6bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-arrow-back" /></template>
