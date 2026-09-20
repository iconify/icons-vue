<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bxduv9kxn.css';
import '../../css/o/o5wv6r8pk.css';
import '../../css/r/rq_0dy_2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bxduv9kxn"/><path class="o5wv6r8pk"/><path class="rq_0dy_2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-cards-line-duotone" /></template>
