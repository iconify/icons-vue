<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkkqx5jfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkkqx5jfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-fill-round" /></template>
