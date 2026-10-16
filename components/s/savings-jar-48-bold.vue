<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd5r3x2_e.css';
import '../../css/b/b4h63gpfv.css';
import '../../css/c/c5l9tbr2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xd5r3x2_e"/><path class="b4h63gpfv"/><path class="c5l9tbr2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:savings-jar-48-bold" /></template>
