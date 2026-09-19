<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyfok-mpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xyfok-mpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:overflow-vertical-fill-12" /></template>
