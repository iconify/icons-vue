<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg9j1xb1g.css';
import '../../css/c/cft1j_bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xg9j1xb1g"/><path class="cft1j_bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:moyai" /></template>
