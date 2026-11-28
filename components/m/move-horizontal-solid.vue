<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3w5q6brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3w5q6brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:move-horizontal-solid" /></template>
