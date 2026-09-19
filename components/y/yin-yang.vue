<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6lwejbts.css';
import '../../css/b/b12gxvr_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6lwejbts"/><circle class="b12gxvr_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:yin-yang" /></template>
