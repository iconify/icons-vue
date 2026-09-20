<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb95hjbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb95hjbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sofa" /></template>
