<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nft7035wh.css';
import '../../css/p/pd96bdi8m.css';
import '../../css/u/ujoab5bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nft7035wh"/><path class="pd96bdi8m"/><path class="ujoab5bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scaffolding-48" /></template>
