<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/z2cemcb1p.css';
import '../../css/b/badaaobgc.css';
import '../../css/t/t70snbb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z2cemcb1p"/><path class="badaaobgc"/><path class="t70snbb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:permanent-job" /></template>
