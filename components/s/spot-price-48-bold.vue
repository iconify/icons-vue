<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc7sk8bgn.css';
import '../../css/h/hiqojibfd.css';
import '../../css/r/rb9owibwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cc7sk8bgn"/><path class="hiqojibfd"/><path class="rb9owibwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spot-price-48-bold" /></template>
