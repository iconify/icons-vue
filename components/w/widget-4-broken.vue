<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p_8xklbbj.css';
import '../../css/g/g8fm3s2qb.css';
import '../../css/y/ynfoavvdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p_8xklbbj"/><path class="g8fm3s2qb"/><path class="ynfoavvdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-4-broken" /></template>
