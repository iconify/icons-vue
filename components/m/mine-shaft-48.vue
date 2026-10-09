<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ori7inbrr.css';
import '../../css/q/q116iryet.css';
import '../../css/v/vyt_0h-7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ori7inbrr"/><path class="q116iryet"/><path class="vyt_0h-7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-shaft-48" /></template>
