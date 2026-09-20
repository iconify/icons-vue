<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypfwpeqha.css';
import '../../css/t/tqahksbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ypfwpeqha"/><path class="tqahksbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openwrt" /></template>
