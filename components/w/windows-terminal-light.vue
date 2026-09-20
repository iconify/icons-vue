<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj9b7k8db.css';
import '../../css/y/ym98bkbma.css';
import '../../css/y/yy5qrkvzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jj9b7k8db"/><path class="ym98bkbma"/><path class="yy5qrkvzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windows-terminal-light" /></template>
