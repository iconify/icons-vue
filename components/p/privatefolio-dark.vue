<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvf5h20sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yvf5h20sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:privatefolio-dark" /></template>
