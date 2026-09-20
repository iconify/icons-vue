<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5_pvnbbf.css';
import '../../css/w/wgglyuewc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5_pvnbbf"/><path class="wgglyuewc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zoom-2025-light" /></template>
