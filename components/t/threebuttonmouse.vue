<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4c47gkwc.css';
import '../../css/r/rvgwmpbdo.css';
import '../../css/h/h-k86boip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4c47gkwc"/><path class="rvgwmpbdo"/><path class="h-k86boip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:threebuttonmouse" /></template>
