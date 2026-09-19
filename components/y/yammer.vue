<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qesz6wb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qesz6wb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:yammer" /></template>
