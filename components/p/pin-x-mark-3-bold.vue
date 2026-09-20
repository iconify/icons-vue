<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4x9v31po.css';
import '../../css/g/g8g82bb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4x9v31po"/><path class="g8g82bb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pin-x-mark-3-bold" /></template>
