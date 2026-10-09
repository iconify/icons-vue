<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm_t_jblc.css';
import '../../css/j/jztm0fbrx.css';
import '../../css/t/tbrtq8bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lm_t_jblc"/><path class="jztm0fbrx"/><path class="tbrtq8bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wood-stove-48" /></template>
