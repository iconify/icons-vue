<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv6_idbzi.css';
import '../../css/h/hcv589g6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1.28,"height":1.28};
const content = `<path class="vv6_idbzi"/><path class="hcv589g6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:snapcraft" /></template>
