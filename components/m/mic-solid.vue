<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz75m85jy.css';
import '../../css/i/ipvgj6bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz75m85jy"/><path class="ipvgj6bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:mic-solid" /></template>
