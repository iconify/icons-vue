<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2s-qrx1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2s-qrx1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:timer-close" /></template>
