<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdg_9ybgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdg_9ybgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:trezor" /></template>
