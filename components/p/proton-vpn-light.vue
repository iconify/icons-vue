<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch2-5kufi.css';
import '../../css/t/tg-9ed7zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ch2-5kufi"/><path class="tg-9ed7zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-vpn-light" /></template>
