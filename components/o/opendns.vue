<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4y3k-p3k.css';
import '../../css/n/nv3l533ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4y3k-p3k"/><path class="nv3l533ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opendns" /></template>
