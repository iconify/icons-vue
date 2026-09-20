<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umfov9uyl.css';
import '../../css/b/bo_y54-xh.css';
import '../../css/q/qyybdwj7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="umfov9uyl"/><path class="bo_y54-xh"/><path class="qyybdwj7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-walkman-cassette" /></template>
