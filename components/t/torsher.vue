<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkccombky.css';
import '../../css/r/r0yz7hbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="gkccombky"/><path class="r0yz7hbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:torsher" /></template>
