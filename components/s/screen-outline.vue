<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkx1uwbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rkx1uwbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:screen-outline" /></template>
