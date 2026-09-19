<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8sbyybhx.css';
import '../../css/d/di5o6abzw.css';
import '../../css/t/tfb53697o.css';
import '../../css/y/ysanb1o8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8sbyybhx"/><path class="di5o6abzw"/><path class="tfb53697o"/><path class="ysanb1o8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:qrcode" /></template>
