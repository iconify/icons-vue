<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6dnwhibh.css';
import '../../css/q/qyrvrgbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6dnwhibh"/><path class="qyrvrgbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:usb" /></template>
