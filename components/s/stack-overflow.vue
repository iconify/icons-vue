<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvx_zmbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvx_zmbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:stack-overflow" /></template>
