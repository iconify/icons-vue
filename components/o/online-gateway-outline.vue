<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzvaq3_vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tzvaq3_vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:online-gateway-outline" /></template>
