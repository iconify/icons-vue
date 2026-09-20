<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hut5hnb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hut5hnb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:screen-broadcast-solid" /></template>
