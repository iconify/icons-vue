<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au5ft3ime.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="au5ft3ime"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-rio" /></template>
