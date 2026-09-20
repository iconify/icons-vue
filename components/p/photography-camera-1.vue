<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saaufmbsj.css';
import '../../css/k/kl-9_wbua.css';
import '../../css/p/pgfaj-tpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="saaufmbsj"/><path class="kl-9_wbua"/><path class="pgfaj-tpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:photography-camera-1" /></template>
