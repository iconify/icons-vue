<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qbtjsobxy.css';
import '../../css/r/rl4wv9bhm.css';
import '../../css/s/sf1qombsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qbtjsobxy"/><path class="rl4wv9bhm"/><path class="sf1qombsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mailbox-01" /></template>
