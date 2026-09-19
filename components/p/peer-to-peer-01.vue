<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wyxq__p8i.css';
import '../../css/t/tnvmgoeyz.css';
import '../../css/c/c61zi6xxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wyxq__p8i"/><path class="tnvmgoeyz"/><path class="c61zi6xxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:peer-to-peer-01" /></template>
