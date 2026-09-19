<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkan-9bwk.css';
import '../../css/l/l307u0bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dkan-9bwk"/><path class="l307u0bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pricetags" /></template>
