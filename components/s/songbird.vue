<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq_mfgb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq_mfgb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:songbird" /></template>
