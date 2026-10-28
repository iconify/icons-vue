<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_gly58ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path vector-effect="non-scaling-stroke" class="d_gly58ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synaplan-light" /></template>
