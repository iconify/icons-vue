<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw_8glqog.css';
import '../../css/t/tmnz0vbmc.css';
import '../../css/f/f_quf2bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qw_8glqog"/><path class="tmnz0vbmc"/><path class="f_quf2bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paypal-dark" /></template>
