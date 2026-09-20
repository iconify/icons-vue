<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3y6xqgne.css';
import '../../css/p/p84959bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3y6xqgne"/><path class="p84959bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mozilla-monitor-light" /></template>
