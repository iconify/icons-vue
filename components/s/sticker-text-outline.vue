<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nua-p_ooz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nua-p_ooz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticker-text-outline" /></template>
