<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tupyodbki.css';
import '../../css/k/k19v9_bwo.css';
import '../../css/c/cizg-mbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tupyodbki"/><path class="k19v9_bwo"/><path class="cizg-mbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-pump-48" /></template>
