<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chl3e-b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":400};
const content = `<path class="chl3e-b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wifi-outline" /></template>
