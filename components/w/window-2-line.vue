<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd-uecbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd-uecbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:window-2-line" /></template>
