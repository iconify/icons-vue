<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg_5ibcij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg_5ibcij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:motorcycle" /></template>
