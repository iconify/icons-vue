<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfc3-ybwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nfc3-ybwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mouse-select-filled" /></template>
