<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyuep_bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyuep_bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:strike-through" /></template>
