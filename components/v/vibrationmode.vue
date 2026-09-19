<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqd6qpbht.css';
import '../../css/b/bbpo9lb1d.css';
import '../../css/p/pe1khgbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pqd6qpbht"/><path class="bbpo9lb1d"/><path class="pe1khgbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:vibrationmode" /></template>
