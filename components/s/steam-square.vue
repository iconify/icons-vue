<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrwisccxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":448};
const content = `<path class="qrwisccxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:steam-square" /></template>
