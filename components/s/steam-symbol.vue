<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc5smubsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wc5smubsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:steam-symbol" /></template>
