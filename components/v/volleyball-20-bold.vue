<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0oa-qzdz.css';
import '../../css/i/i_pma5d1l.css';
import '../../css/f/f_w74lrnj.css';
import '../../css/c/c2_eabbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="i_pma5d1l"/><path class="f_w74lrnj"/><path class="c2_eabbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volleyball-20-bold" /></template>
