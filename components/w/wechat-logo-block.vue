<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx-a_8bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx-a_8bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wechat-logo-block" /></template>
