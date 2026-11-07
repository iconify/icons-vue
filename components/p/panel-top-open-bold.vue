<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgaa_tbxh.css';
import '../../css/l/lzylfm93k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tgaa_tbxh"/><path class="lzylfm93k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-top-open-bold" /></template>
