<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s900nabfq.css';
import '../../css/w/w5mx-v3dw.css';
import '../../css/m/ma8aecusd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s900nabfq"/><path class="w5mx-v3dw"/><path class="ma8aecusd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trowel-20-bold" /></template>
