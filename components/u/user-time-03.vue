<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew31hdmyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew31hdmyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-time-03" /></template>
