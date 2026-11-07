<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t3tivrbho.css';
import '../../css/d/dv86dk8ai.css';
import '../../css/y/yv3vxtb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t3tivrbho"/><path class="dv86dk8ai"/><path class="yv3vxtb5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-broken" /></template>
