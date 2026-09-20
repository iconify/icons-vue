<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vthoncfqk.css';
import '../../css/m/mlv6tlbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="n1lsf0bnc"><path class="vthoncfqk"/><path class="mlv6tlbcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:remove-application" /></template>
