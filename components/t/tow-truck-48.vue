<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnnymsbii.css';
import '../../css/l/lai5ftb8v.css';
import '../../css/d/d_2bnvy8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wnnymsbii"/><path class="lai5ftb8v"/><path class="d_2bnvy8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tow-truck-48" /></template>
