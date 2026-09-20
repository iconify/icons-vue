<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-v0owbtv.css';
import '../../css/e/ebu833blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-v0owbtv"/><path class="ebu833blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:prism" /></template>
