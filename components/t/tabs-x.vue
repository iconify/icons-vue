<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz_9l1y1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz_9l1y1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tabs-x" /></template>
