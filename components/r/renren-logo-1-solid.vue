<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3yu_1dgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3yu_1dgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:renren-logo-1-solid" /></template>
