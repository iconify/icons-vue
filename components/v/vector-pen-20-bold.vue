<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izj2xgmec.css';
import '../../css/i/il1n2kszo.css';
import '../../css/j/jykge1big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="izj2xgmec"/><path class="il1n2kszo"/><path class="jykge1big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vector-pen-20-bold" /></template>
