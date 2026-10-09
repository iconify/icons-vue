<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsm-zt1sg.css';
import '../../css/e/eg_g120yy.css';
import '../../css/h/hy4sx7b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dsm-zt1sg"/><path class="eg_g120yy"/><path class="hy4sx7b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scissors-48" /></template>
