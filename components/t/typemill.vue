<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqu2_e4mu.css';
import '../../css/o/ohi1dmbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="pqu2_e4mu"/><path class="ohi1dmbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typemill" /></template>
