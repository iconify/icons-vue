<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp-m33bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pp-m33bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:threat-usb-remix" /></template>
