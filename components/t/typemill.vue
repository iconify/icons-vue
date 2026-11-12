<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqu2_e4mu.css';
import '../../css/r/r698ifziu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="pqu2_e4mu"/><path class="r698ifziu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typemill" /></template>
