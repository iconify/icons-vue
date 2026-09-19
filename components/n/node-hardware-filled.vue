<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr-yfwb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr-yfwb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:node-hardware-filled" /></template>
