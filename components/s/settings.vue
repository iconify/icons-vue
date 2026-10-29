<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl3fapacx.css';
import '../../css/c/cerp886bk.css';
import '../../css/f/fdjy-kuog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yl3fapacx"/><path class="cerp886bk wm-a"/><path class="fdjy-kuog wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:settings" /></template>
