<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shhu5beuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shhu5beuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:wlan-off" /></template>
