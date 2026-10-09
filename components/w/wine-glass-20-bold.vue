<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kexdcibjn.css';
import '../../css/g/ggqjhtbos.css';
import '../../css/m/mraa0lb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kexdcibjn"/><path class="ggqjhtbos"/><path class="mraa0lb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wine-glass-20-bold" /></template>
