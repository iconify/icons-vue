<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk4c41b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk4c41b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pipe" /></template>
