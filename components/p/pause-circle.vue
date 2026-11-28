<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guifg13yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guifg13yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pause-circle" /></template>
