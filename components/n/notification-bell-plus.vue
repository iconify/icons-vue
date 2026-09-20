<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yejbj_b4f.css';
import '../../css/c/cay-wqb7i.css';
import '../../css/y/y6nxu5ppu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yejbj_b4f"/><path class="cay-wqb7i"/><path class="y6nxu5ppu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-plus" /></template>
