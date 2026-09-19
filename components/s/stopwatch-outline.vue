<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd6hptbdy.css';
import '../../css/y/ydx4aab2y.css';
import '../../css/p/pnj3j0bnr.css';
import '../../css/e/ejbf23bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hd6hptbdy"/><path class="ydx4aab2y"/><circle class="pnj3j0bnr"/><path class="ejbf23bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:stopwatch-outline" /></template>
