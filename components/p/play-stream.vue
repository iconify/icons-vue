<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt2s5wknr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zt2s5wknr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:play-stream" /></template>
