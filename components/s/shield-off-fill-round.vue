<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxdneib_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxdneib_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-fill-round" /></template>
