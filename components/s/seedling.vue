<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw_lpwbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iw_lpwbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:seedling" /></template>
