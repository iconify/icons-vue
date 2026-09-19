<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6dnwhibh.css';
import '../../css/s/s1ktrc_2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6dnwhibh"/><path class="s1ktrc_2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:usb-filled" /></template>
