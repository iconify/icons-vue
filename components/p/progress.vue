<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljov1rb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljov1rb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:progress" /></template>
