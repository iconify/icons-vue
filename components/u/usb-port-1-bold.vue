<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxbsrubkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxbsrubkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:usb-port-1-bold" /></template>
