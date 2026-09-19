<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkt_eriht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkt_eriht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:openwrt-logo" /></template>
