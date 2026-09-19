<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niza58bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="niza58bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:trapezoid" /></template>
