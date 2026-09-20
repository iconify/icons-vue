<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eva8smxqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eva8smxqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matrix" /></template>
