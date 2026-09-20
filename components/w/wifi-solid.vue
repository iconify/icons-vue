<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q78h75nsj.css';
import '../../css/w/wlug79bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q78h75nsj"/><path class="wlug79bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:wifi-solid" /></template>
