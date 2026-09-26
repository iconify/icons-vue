<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt2-4yxgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt2-4yxgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-vertical-linear" /></template>
