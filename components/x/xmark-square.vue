<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gex8edqua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gex8edqua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:xmark-square" /></template>
