<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7bfszaos.css';
import '../../css/t/tbg_x-bdw.css';
import '../../css/s/sux4gdc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k7bfszaos"/><path class="tbg_x-bdw"/><path class="sux4gdc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:repeat-one-20" /></template>
