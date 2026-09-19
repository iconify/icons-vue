<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xdw8tmbkh.css';
import '../../css/j/jiaf59bmv.css';
import '../../css/x/xzp7pacbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xdw8tmbkh"/><path class="jiaf59bmv"/><path class="xzp7pacbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-unlock-02" /></template>
