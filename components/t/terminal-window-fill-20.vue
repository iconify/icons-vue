<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzmt377rd.css';
import '../../css/o/oreh4pgns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lzmt377rd"/><path class="oreh4pgns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-window-fill-20" /></template>
