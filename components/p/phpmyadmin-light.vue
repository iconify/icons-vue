<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncc_k81kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ncc_k81kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpmyadmin-light" /></template>
