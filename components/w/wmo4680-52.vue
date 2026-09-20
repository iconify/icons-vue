<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv-rcc7eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="kv-rcc7eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wmo4680-52" /></template>
