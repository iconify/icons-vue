<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp0h-lbxu.css';
import '../../css/n/nlt59cbzt.css';
import '../../css/l/l101akbav.css';
import '../../css/b/bs-gs5b8g.css';
import '../../css/h/h4ymgcbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp0h-lbxu"/><path class="nlt59cbzt"/><path class="l101akbav"/><path class="bs-gs5b8g"/><path class="h4ymgcbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-off-outline" /></template>
