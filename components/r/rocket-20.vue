<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_5-m_blk.css';
import '../../css/r/rjoq2cbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i_5-m_blk"/><path class="rjoq2cbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rocket-20" /></template>
