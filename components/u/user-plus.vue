<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wqeor8b3g.css';
import '../../css/o/o7xo0fbbb.css';
import '../../css/l/ll86lgblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="wqeor8b3g"/><circle class="o7xo0fbbb"/><path class="ll86lgblt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-plus" /></template>
