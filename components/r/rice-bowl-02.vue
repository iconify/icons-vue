<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/ye4fm_b9r.css';
import '../../css/z/z8yx5mbkz.css';
import '../../css/b/b-m5x99nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ye4fm_b9r"/><path class="z8yx5mbkz"/><path class="b-m5x99nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rice-bowl-02" /></template>
