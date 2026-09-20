<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qewigu5gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qewigu5gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:selfh-st-light" /></template>
