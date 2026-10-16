<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s82-gfb1o.css';
import '../../css/v/vs4bry39s.css';
import '../../css/f/fj5kn0w7n.css';
import '../../css/u/uedre7bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s82-gfb1o"/><path class="vs4bry39s"/><path class="fj5kn0w7n"/><path class="uedre7bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mosque-48" /></template>
