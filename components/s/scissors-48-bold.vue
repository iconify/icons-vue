<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3fcb3g_r.css';
import '../../css/l/l37lfua-l.css';
import '../../css/c/c64c-7baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f3fcb3g_r"/><path class="l37lfua-l"/><path class="c64c-7baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scissors-48-bold" /></template>
