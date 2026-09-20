<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9l3hbf0t.css';
import '../../css/y/y0j0mcbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9l3hbf0t"/><path class="y0j0mcbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-harvester" /></template>
