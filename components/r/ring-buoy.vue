<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/se00zpnsh.css';
import '../../css/c/cyd1o9bus.css';
import '../../css/k/kqz3dbcpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="se00zpnsh"/><path class="cyd1o9bus"/><path class="kqz3dbcpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:ring-buoy" /></template>
