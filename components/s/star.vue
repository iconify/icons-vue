<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duug3hbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="duug3hbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:star" /></template>
