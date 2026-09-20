<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzs1w6bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzs1w6bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-search" /></template>
