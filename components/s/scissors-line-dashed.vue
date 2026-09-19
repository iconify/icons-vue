<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/taopsuymn.css';
import '../../css/y/y9ynmbbhf.css';
import '../../css/s/sxl1tlgcy.css';
import '../../css/m/mel2rybyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="taopsuymn"/><circle class="y9ynmbbhf"/><path class="sxl1tlgcy"/><circle class="mel2rybyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scissors-line-dashed" /></template>
