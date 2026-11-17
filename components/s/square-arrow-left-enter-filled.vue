<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3lpxulyc.css';
import '../../css/i/i0ekbjbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3lpxulyc"/><path class="i0ekbjbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-left-enter-filled" /></template>
