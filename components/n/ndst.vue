<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmyfq_blj.css';
import '../../css/a/a28a78bjh.css';
import '../../css/m/m2_srvnyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tmyfq_blj"/><path class="a28a78bjh"/><path class="m2_srvnyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ndst" /></template>
