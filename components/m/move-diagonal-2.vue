<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7ymfdc9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7ymfdc9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-diagonal-2" /></template>
