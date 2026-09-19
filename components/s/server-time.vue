<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okximigwt.css';
import '../../css/d/dlp7nstpk.css';
import '../../css/a/avvjpobem.css';
import '../../css/c/cr9nds-9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="okximigwt"/><circle class="dlp7nstpk"/><path class="avvjpobem"/><path class="cr9nds-9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:server-time" /></template>
