<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otnv16btc.css';
import '../../css/a/aagla3kgr.css';
import '../../css/m/mmkzhsffi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otnv16btc"/><path class="aagla3kgr"/><path class="mmkzhsffi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-rich" /></template>
