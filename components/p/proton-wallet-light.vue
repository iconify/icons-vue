<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dne8y0bds.css';
import '../../css/b/b1ivybqei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dne8y0bds"/><path class="b1ivybqei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-wallet-light" /></template>
