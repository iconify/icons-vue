<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xteprklyo.css';
import '../../css/m/moem5k2vk.css';
import '../../css/z/zy870cbtg.css';
import '../../css/a/al9qvobnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xteprklyo"/><path class="moem5k2vk"/><circle class="zy870cbtg"/><ellipse class="al9qvobnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mv-1x1" /></template>
