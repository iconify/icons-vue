<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl55q5bty.css';
import '../../css/l/lr1-z_9gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yl55q5bty"/><path class="lr1-z_9gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinterest" /></template>
