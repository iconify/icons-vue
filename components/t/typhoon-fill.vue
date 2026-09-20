<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1tyi1bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1tyi1bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:typhoon-fill" /></template>
