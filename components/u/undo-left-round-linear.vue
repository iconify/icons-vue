<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncp3p2b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncp3p2b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-left-round-linear" /></template>
