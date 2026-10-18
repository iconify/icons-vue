<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cawzwbo3e.css';
import '../../css/o/o2iujpb6b.css';
import '../../css/f/ftz9zcbou.css';
import '../../css/h/h8v-jytyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cawzwbo3e"/><path class="o2iujpb6b"/><path class="ftz9zcbou"/><path class="h8v-jytyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:net-metering-20" /></template>
