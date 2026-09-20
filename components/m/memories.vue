<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp1v2sdoj.css';
import '../../css/k/kya2hp-hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1v2sdoj"/><path class="kya2hp-hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:memories" /></template>
