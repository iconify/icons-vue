<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pvkc1k-jx.css';
import '../../css/g/gg604n2bm.css';
import '../../css/z/za12y0ykl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pvkc1k-jx"/><path class="gg604n2bm"/><path class="za12y0ykl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-delay-02" /></template>
