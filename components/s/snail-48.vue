<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhd-y3l3p.css';
import '../../css/s/s01pkn5yu.css';
import '../../css/t/t3v183p3v.css';
import '../../css/w/wd4dq3mdq.css';
import '../../css/b/be_v7abzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhd-y3l3p"/><path class="s01pkn5yu"/><path class="t3v183p3v"/><path class="wd4dq3mdq"/><path class="be_v7abzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:snail-48" /></template>
