<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpgtxy_zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kpgtxy_zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-help-buoy" /></template>
