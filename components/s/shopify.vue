<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwx7xzbau.css';
import '../../css/p/pjoaw5biz.css';
import '../../css/x/xtnbm313d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwx7xzbau"/><path class="pjoaw5biz"/><path class="xtnbm313d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shopify" /></template>
