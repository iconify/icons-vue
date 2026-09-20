<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjuz_-ocm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjuz_-ocm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pyramid-shape" /></template>
