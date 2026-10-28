<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnbn3ib9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path vector-effect="non-scaling-stroke" class="wnbn3ib9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synaplan" /></template>
