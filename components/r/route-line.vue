<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpx_mobwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpx_mobwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:route-line" /></template>
