<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8l48i23l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r8l48i23l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:network-device-play-filled" /></template>
