<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqm4_kbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqm4_kbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xido" /></template>
