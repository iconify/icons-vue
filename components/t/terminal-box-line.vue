<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooienabsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooienabsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-box-line" /></template>
