<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj35uabzq.css';
import '../../css/s/sj53jabxf.css';
import '../../css/p/ptnzl-b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gj35uabzq"/><path class="sj53jabxf"/><path class="ptnzl-b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windows-terminal-dark" /></template>
