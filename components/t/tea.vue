<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bvzr0fklu.css';
import '../../css/l/lll6g396l.css';
import '../../css/g/gyj__2tko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bvzr0fklu"/><path class="lll6g396l"/><path class="gyj__2tko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tea" /></template>
