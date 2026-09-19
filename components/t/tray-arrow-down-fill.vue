<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jev2d4znk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jev2d4znk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray-arrow-down-fill" /></template>
