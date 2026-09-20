<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kouiwvecw.css';
import '../../css/k/kz4_g2b8b.css';
import '../../css/y/yz8hndo5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kouiwvecw"/><path class="kz4_g2b8b"/><path class="yz8hndo5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seq" /></template>
