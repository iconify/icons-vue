<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8eqpxbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8eqpxbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-font" /></template>
