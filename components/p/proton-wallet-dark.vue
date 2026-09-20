<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy8db6b8d.css';
import '../../css/k/kch4ro44n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xy8db6b8d"/><path class="kch4ro44n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-wallet-dark" /></template>
