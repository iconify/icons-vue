<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3kb4cgpl.css';
import '../../css/l/lv728hb5d.css';
import '../../css/c/c9w3-fsnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="r3kb4cgpl"><path class="lv728hb5d"/><path class="c9w3-fsnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-start-bold" /></template>
