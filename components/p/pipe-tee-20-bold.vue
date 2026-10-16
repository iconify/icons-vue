<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl5mofb1p.css';
import '../../css/q/qf_72ga9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nl5mofb1p"/><path class="qf_72ga9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-tee-20-bold" /></template>
