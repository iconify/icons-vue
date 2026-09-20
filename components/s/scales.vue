<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g44uy_bjc.css';
import '../../css/k/kjgm23o3b.css';
import '../../css/m/maptswbqy.css';
import '../../css/p/p599o3h7x.css';
import '../../css/t/t1tln_bqb.css';
import '../../css/c/cx0g5kprr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g44uy_bjc"/><circle class="kjgm23o3b"/><path class="maptswbqy"/><circle class="p599o3h7x"/><path class="t1tln_bqb"/><path class="cx0g5kprr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:scales" /></template>
