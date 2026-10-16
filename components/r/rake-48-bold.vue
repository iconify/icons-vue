<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl32e1bkb.css';
import '../../css/z/zafm50xfx.css';
import '../../css/b/bn2n7mbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wl32e1bkb"/><path class="zafm50xfx"/><path class="bn2n7mbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rake-48-bold" /></template>
