<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrk_i1wgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zrk_i1wgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:redo-circle-square-filled" /></template>
