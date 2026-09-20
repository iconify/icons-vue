<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co93ein0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co93ein0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scale-off" /></template>
