<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_nee0cyh.css';
import '../../css/k/kafmo0bpp.css';
import '../../css/l/lkpq_rbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j_nee0cyh"/><path class="kafmo0bpp"/><path class="lkpq_rbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-climbing" /></template>
