<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vla37tbfm.css';
import '../../css/w/wgw8u43wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vla37tbfm"/><path class="wgw8u43wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:times-circle-duotone" /></template>
