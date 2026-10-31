<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sam6x3bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sam6x3bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:sort-az" /></template>
