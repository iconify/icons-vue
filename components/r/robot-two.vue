<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/z4gla85ro.css';
import '../../css/d/d6rjz8b6d.css';
import '../../css/k/kmzp8bb_p.css';
import '../../css/t/tewkg6wrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="z4gla85ro"/><path class="d6rjz8b6d"/><circle class="kmzp8bb_p"/><path class="tewkg6wrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:robot-two" /></template>
