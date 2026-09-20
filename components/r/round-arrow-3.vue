<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk8mt4fmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hk8mt4fmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:round-arrow-3" /></template>
