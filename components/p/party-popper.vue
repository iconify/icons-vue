<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j5ryysb0v.css';
import '../../css/w/wccisyhhx.css';
import '../../css/g/gupjygfja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j5ryysb0v"/><path class="wccisyhhx"/><path class="gupjygfja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:party-popper" /></template>
