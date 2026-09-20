<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmp5x0bgg.css';
import '../../css/k/kqqve2g3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmp5x0bgg"/><path class="kqqve2g3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sort-amount-up-alt" /></template>
