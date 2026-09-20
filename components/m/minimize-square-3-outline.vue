<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yplnl1biz.css';
import '../../css/j/j-shekb6c.css';
import '../../css/v/vsyunqiht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yplnl1biz"/><path class="j-shekb6c"/><path clip-rule="evenodd" class="vsyunqiht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-3-outline" /></template>
