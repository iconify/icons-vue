<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe8f_eb4j.css';
import '../../css/z/z8jeaq2_u.css';
import '../../css/j/j-2pke6of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qe8f_eb4j"/><path class="z8jeaq2_u"/><path class="j-2pke6of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-source-48-bold" /></template>
