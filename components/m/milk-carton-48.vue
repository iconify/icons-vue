<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytre_iyqf.css';
import '../../css/a/aqm8hp2ux.css';
import '../../css/a/a6d6nheff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ytre_iyqf"/><path class="aqm8hp2ux"/><path class="a6d6nheff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:milk-carton-48" /></template>
