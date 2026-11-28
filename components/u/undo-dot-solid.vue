<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg9umdx1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg9umdx1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:undo-dot-solid" /></template>
