<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq7y1qqox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq7y1qqox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-search" /></template>
