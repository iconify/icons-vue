<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rm_q7b7hi.css';
import '../../css/y/ydu9-nbzw.css';
import '../../css/v/vm23ifb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rm_q7b7hi"/><path class="ydu9-nbzw"/><path class="vm23ifb4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:truck-electric" /></template>
