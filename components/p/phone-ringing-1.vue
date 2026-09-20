<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ton_gr_8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ton_gr_8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:phone-ringing-1" /></template>
