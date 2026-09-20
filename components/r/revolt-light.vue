<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wes_5_bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wes_5_bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:revolt-light" /></template>
