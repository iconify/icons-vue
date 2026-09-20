<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ere8b8b-s.css';
import '../../css/s/su2ci-bpz.css';
import '../../css/q/qyvbf9bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ere8b8b-s"/><path class="su2ci-bpz"/><path class="qyvbf9bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zimaos" /></template>
