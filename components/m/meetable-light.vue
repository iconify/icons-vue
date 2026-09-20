<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk7-njbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wk7-njbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meetable-light" /></template>
