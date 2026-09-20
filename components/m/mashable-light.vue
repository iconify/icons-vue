<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5v7awbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l5v7awbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mashable-light" /></template>
