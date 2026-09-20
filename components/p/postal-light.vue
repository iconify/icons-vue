<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdblbht-m.css';
import '../../css/y/yjqp6ojwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qdblbht-m"/><path class="yjqp6ojwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postal-light" /></template>
