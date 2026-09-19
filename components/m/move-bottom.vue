<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jv2_h6bjf.css';
import '../../css/f/f8yqsxb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jv2_h6bjf"/><circle transform="matrix(0 1 1 0 9 2)" class="f8yqsxb0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:move-bottom" /></template>
