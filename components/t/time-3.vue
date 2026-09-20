<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvdcm44zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bvdcm44zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:time-3" /></template>
