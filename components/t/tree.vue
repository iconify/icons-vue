<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t99n1acxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t99n1acxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tree" /></template>
