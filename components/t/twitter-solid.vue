<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf3y0_dgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kf3y0_dgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:twitter-solid" /></template>
