<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms616ybsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ms616ybsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-add" /></template>
