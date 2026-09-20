<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3o4tj12j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3o4tj12j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:travel" /></template>
