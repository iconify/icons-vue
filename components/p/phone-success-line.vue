<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tonk8_bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tonk8_bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-success-line" /></template>
