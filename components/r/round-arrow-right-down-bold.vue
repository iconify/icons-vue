<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbcm4tu4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbcm4tu4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-right-down-bold" /></template>
