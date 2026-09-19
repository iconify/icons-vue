<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqmaimblk.css';
import '../../css/j/j7wys6bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqmaimblk"/><path class="j7wys6bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-rocket" /></template>
