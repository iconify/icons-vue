<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep6yosbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep6yosbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:play" /></template>
