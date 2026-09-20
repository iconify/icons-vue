<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n26s6ub1x.css';
import '../../css/i/iadi1vbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n26s6ub1x"/><path class="iadi1vbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wikidocs" /></template>
