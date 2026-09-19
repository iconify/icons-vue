<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9irqhbom.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/o/oqwog-bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9irqhbom"/><path class="bwibdw4bb"/><path class="oqwog-bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sleepy" /></template>
