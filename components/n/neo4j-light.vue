<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaw4gtbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yaw4gtbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:neo4j-light" /></template>
