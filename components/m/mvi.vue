<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubqgo3idq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubqgo3idq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mvi" /></template>
