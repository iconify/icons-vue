<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnuf_0rpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnuf_0rpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:train" /></template>
