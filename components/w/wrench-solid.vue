<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2p1z0-xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i2p1z0-xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wrench-solid" /></template>
