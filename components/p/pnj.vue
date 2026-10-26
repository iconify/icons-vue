<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt_lpuqei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1510,"height":1515};
const content = `<path class="xt_lpuqei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pnj" /></template>
