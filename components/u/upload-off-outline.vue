<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfedg_btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfedg_btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:upload-off-outline" /></template>
