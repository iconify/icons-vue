<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z15me-ble.css';
import '../../css/c/ctxclkbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z15me-ble"/><path class="ctxclkbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vr-headset-20" /></template>
