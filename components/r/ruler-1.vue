<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv21ox71h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="qv21ox71h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ruler-1" /></template>
