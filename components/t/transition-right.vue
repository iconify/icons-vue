<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tg7r5obnp.css';
import '../../css/a/ar0z5_bbv.css';
import '../../css/a/aotcudf0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tg7r5obnp"/><path class="ar0z5_bbv"/><path class="aotcudf0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:transition-right" /></template>
