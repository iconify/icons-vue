<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fnklneb_k.css';
import '../../css/k/kiol6ablm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><rect transform="rotate(45 15.712 1.924)" class="fnklneb_k"/><path class="kiol6ablm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:ruler-diagonal" /></template>
