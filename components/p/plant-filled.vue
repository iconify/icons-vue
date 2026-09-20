<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msytv967m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="msytv967m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-filled" /></template>
