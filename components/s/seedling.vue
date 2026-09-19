<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvdcz70ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvdcz70ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:seedling" /></template>
