<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyk27hxcx.css';
import '../../css/l/lxvvbdcsj.css';
import '../../css/u/u90_kz3vk.css';
import '../../css/v/vsnq63-xh.css';
import '../../css/v/vzkmoxbec.css';
import '../../css/u/u81171hdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qyk27hxcx"/><path class="lxvvbdcsj"/><path class="u90_kz3vk"/><path class="vsnq63-xh"/><path class="vzkmoxbec"/><circle class="u81171hdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:smartphone-tablet" /></template>
