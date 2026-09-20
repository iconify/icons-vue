<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw7izwpwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sw7izwpwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:usb-port-remix" /></template>
