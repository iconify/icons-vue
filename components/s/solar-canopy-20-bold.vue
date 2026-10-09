<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtet-k65m.css';
import '../../css/a/an9q9g7yw.css';
import '../../css/f/fxx-u-bxj.css';
import '../../css/s/sqxdqpa1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jtet-k65m"/><path class="an9q9g7yw"/><path class="fxx-u-bxj"/><path class="sqxdqpa1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-canopy-20-bold" /></template>
