<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktc-_ac_k.css';
import '../../css/p/pasu78bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ktc-_ac_k"/><path class="pasu78bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:power-switch" /></template>
