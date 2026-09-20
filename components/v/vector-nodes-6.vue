<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5zq6fb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="i5zq6fb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vector-nodes-6" /></template>
