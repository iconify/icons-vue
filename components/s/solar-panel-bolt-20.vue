<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwg6nmvzy.css';
import '../../css/k/k1o0uibpr.css';
import '../../css/a/a2v302bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wwg6nmvzy"/><path class="k1o0uibpr"/><path class="a2v302bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-bolt-20" /></template>
