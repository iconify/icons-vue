<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwop8ib1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vwop8ib1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray-full-fill" /></template>
