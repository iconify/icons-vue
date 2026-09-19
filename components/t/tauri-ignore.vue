<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvcq89ble.css';
import '../../css/o/oa964uw4k.css';
import '../../css/q/q8ppmua1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cvcq89ble"><path class="oa964uw4k"/><path class="q8ppmua1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:tauri-ignore" /></template>
