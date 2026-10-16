<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgiazbbrf.css';
import '../../css/z/znvkcjljr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qgiazbbrf"/><path class="znvkcjljr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-close-20" /></template>
