<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg989kuhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg989kuhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pad-line" /></template>
