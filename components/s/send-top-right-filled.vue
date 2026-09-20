<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ono-tjryk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ono-tjryk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:send-top-right-filled" /></template>
