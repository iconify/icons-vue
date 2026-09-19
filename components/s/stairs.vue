<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/solvc-qmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="solvc-qmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:stairs" /></template>
