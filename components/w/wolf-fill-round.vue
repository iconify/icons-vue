<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlu1beb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlu1beb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wolf-fill-round" /></template>
