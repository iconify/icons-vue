<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy-61duhk.css';
import '../../css/m/modq6pbhs.css';
import '../../css/l/lixkakb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="uy-61duhk"/><path class="modq6pbhs"/><path class="lixkakb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:redux" /></template>
