<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf-t8tbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf-t8tbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:version-line" /></template>
