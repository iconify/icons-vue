<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o67-rbbrh.css';
import '../../css/k/kv7scgbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o67-rbbrh"/><path class="kv7scgbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:neo4j" /></template>
