<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrtjap9eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zrtjap9eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:route" /></template>
