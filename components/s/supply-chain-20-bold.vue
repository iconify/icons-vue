<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr0p-wb-a.css';
import '../../css/p/pp2amswub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gr0p-wb-a"/><path class="pp2amswub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:supply-chain-20-bold" /></template>
