<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsk84s32m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsk84s32m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-duocolor-round" /></template>
