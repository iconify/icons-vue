<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vixpal6lt.css';
import '../../css/p/po4snyb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vixpal6lt"/><path clip-rule="evenodd" class="po4snyb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-play-fail" /></template>
