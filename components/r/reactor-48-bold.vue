<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu57r0fpa.css';
import '../../css/b/by5oxcb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iu57r0fpa"/><path class="by5oxcb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reactor-48-bold" /></template>
