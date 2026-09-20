<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dync3v64e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dync3v64e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-security-filled" /></template>
