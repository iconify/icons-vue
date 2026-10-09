<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wht6-eeil.css';
import '../../css/y/y3tufnbaa.css';
import '../../css/c/cw-o4ybrh.css';
import '../../css/k/kj4pd_xxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wht6-eeil"/><path class="y3tufnbaa"/><path class="cw-o4ybrh"/><path class="kj4pd_xxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-battery-20-bold" /></template>
