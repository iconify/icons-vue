<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-51zibyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-51zibyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:objects-horizontal-center" /></template>
