<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca34txrqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ca34txrqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sandwich" /></template>
