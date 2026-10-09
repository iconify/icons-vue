<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe80ngmuz.css';
import '../../css/a/a0sj_5bhv.css';
import '../../css/r/r_d2c4b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pe80ngmuz"/><path class="a0sj_5bhv"/><path class="r_d2c4b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:office-20" /></template>
