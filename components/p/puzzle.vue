<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpx05ibmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpx05ibmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:puzzle" /></template>
