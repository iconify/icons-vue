<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/add9_ablq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="add9_ablq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-3-warning" /></template>
