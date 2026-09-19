<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2jqtext.css';
import '../../css/w/wndsmq8hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co2jqtext duoicon-secondary-layer"/><path class="duoicon-primary-layer wndsmq8hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:settings" /></template>
