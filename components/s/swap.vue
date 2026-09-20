<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/m/mq6hjubga.css';
import '../../css/i/i6zz6ccrg.css';
import '../../css/j/jztr7pbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="mq6hjubga"/><path class="i6zz6ccrg"/><path class="jztr7pbms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:swap" /></template>
