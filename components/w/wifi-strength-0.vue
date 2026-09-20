<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmd-lzd5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmd-lzd5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-0" /></template>
