<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0n0lcbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="w0n0lcbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tray-phone-26" /></template>
