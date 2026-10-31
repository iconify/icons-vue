<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf89xgbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf89xgbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tooth-bulk-round" /></template>
