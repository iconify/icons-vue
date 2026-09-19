<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf9n4lb9d.css';
import '../../css/z/zdtpxix4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yf9n4lb9d"/><circle class="zdtpxix4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:upperrightwhitecircle" /></template>
