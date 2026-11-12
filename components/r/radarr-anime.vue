<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db2xgugay.css';
import '../../css/g/gi2xlrbzn.css';
import '../../css/u/u4j5hjbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="db2xgugay"/><path class="gi2xlrbzn"/><path class="u4j5hjbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radarr-anime" /></template>
