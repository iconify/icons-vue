<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgp1p-jmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgp1p-jmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-brush" /></template>
